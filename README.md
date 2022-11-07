```shell
echo "# git-command" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Liu-Shihao/git-command.git
git push -u origin main

git remote add origin https://github.com/Liu-Shihao/git-command.git
git branch -M main
git push -u origin main
<<<<<<< HEAD
```

rebase 官方解释为变基,可以理解为移动你的分支根节点,维护一个更好的提交记录。rebase把你当前最新分支与其他分支合并时候,会把其他分支的提交记录放在我们当前分支时间线最开始的位置。也就是说,会把我们的提交记录整合在公共分支的后面。
简单来讲,合并本地其他分支 为了不产生多余的分叉,及合并记录时可以使用rebase。



rebase与merge的差异

rebase 会把你当前分支的 commit 放到公共分支的最后面,所以叫变基。就好像你从公共分支又重新拉出来这个分支一样。
merge 会把公共分支和你当前的 commit 合并在一起，形成一个新的 commit 提交。

