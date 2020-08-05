# gitpractice



### git提交方式



#### 1.clone项目

```shell
git clone

git pull [remote][branch] 取回远程仓库变化，并与本地分支合并
```



#### 2.切换自己分支

```shell
git branch 列出本地所有分支
git branch -r 列出远程所有分支
git branch 名字  新建分支
git chekout -b 名字 新建一个分支，并切换到分支
git chekout 名字 切换分支
git push origin --delete 名字  删除远程分支

```



#### 3.编辑之后提交

```shell
git add. 添加文件

git commit -m "提交信息"

git push origin master
git push [remote] [branch]



```



#### 4.可以在github上先新建分支，之后push上，再请求合并





```shell
git push origin dev-huang:dev-huang 本地分支 推送到远程分支
```

#### 5.注意一些不必要推送的文件，在gitignore声明