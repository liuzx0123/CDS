# CDS
就是一个简单的常识

克隆仓库：git clone <git地址>
初始化仓库：git init 

添加文件到暂存区：git add -A
把暂存区的文件提交到仓库：git commit -m "提交信息"
查看提交的历史记录：git log --stat

工作区回滚：git checkout <filename>
撤销最后一次提交：git reset HEAD^1

以当前分支为基础新建分支：git checkout -b <branchname>
列举所有的分支：git branch
单纯地切换到某个分支：git checkout <branchname>
删掉特定的分支：git branch -D <branchname>
合并分支：git merge <branchname>

推送当前分支最新的提交到远程：git push
拉取远程分支最新的提交到本地：git pull

将某分支合理化 git push --set-upstream origin fenzhi
同步远程分支： git pull --rebase origin main

试一试aaa