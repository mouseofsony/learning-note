# git学习笔记

## 将特定的文件回退版本

如果某个文件已经提交 git checkout 版本id -- 文件名

## 撤销追踪

如果还没有提交，想回到上一个版本 =====>git checkout -- 文件名

如果git add加入到暂存区 git checkout -- 文件名就没有用了

此时需要撤销追踪====> *git reset HEAD 文件名*

## 整个版本回退

> git reset --hard e6b0c52f

## 版本回退之后依然可以再回到没有回退之前的版本

需要用git reflog指令区查看提交