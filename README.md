# Git-GUI

## 描述

一个基于Tcl/Tk的Git的图形用户界面。git gui可以允许用户更改其存储库新提交,修改现有的,创建分支,执行本地的合并,抓取/推到远程存储库。
不像gitk,git gui关注提交代码单行注释和没有显示项目的历史。 然而它供应开始菜单操作gitk会议从在git gui。

## 获取地址

https://git-scm.com/docs/git-gui

http://repo.or.cz/git-gui.git/bundles

命令

```
git init git-gui
cd git-gui
git remote add origin http://repo.or.cz/git-gui.git
git fetch

git remote set-url origin git@github.com:wskplho/git-gui.git

git fetch --prune origin
git remote set-head origin --auto

git branch -r
git checkout master
```


