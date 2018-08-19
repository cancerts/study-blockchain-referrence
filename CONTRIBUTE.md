# 参与贡献

本站希望将整个区块链核心内容进行规整，
但区块链技术自身仍在快速发展中，生态环境也在蓬勃成长。所以欢迎大家参与到项目的维护中来.

首先，在 GitHub 上 fork 到自己的仓库，然后 clone 到本地，并设置用户信息。

> $ git clone https://github.com/cancerts/study-blockchain-referrence.git 

>$ cd study-blockchain-referrence

>$ git config user.name "yourname"

>$ git config user.email "your email"

更新内容后提交，并推送到自己的仓库。

> $ #do some change on the content

> $ git commit -m "Fix issue #1: change one link to another"

> $ git push

最后，在 GitHub 网站上提交 pull request 即可。

另外，建议定期使用项目仓库内容更新自己仓库内容。

>$ git remote add upstream https://github.com/cancerts/study-blockchain-referrence

>$ git fetch upstream

>$ git checkout master

>$ git rebase upstream/master

>$ git push -f origin master
