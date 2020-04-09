## 查看远程仓库信息
git remote -v 

## 设置远程仓库地址
git remote add origin xxxx

## 修改远程仓库地址
git remote set-url origin xxxx

## 从远程仓库拉取代码
git pull origin masia

> 相当于
```bash
# 从远程分支上拉取代码，与本地做对比
git fetch origin masia
# 
git merge
```
