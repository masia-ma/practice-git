# practice-git
with git opration parctice

## 三个概念
远程仓库 本地仓库 本地工作空间

## git fetch 
git fetch origin sail
是将远程分支拉取到本地仓库，但此时还没更新本地的工作空间

git log -p FETCH_HEAD 
查看刚刚从远程仓库拉取到本地仓库的代码的修改部分

git merge FETCH_HEAD
合并刚刚拉取到的代码到本地的工作空间