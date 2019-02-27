# Git笔记



![](E:\DevelopTool\WindtalkersAcher_DevelopToolNotes\Git\assets\无标题.png)



### 版本回退

* 重置当前工作区与暂存区： Git  reset HEAD test.txt
* 版本回退： Git reset --hard HEAD^



### 分支管理

* 创建：Git branch dev
* 创建远程分支到本地：Git checkout -b dev origin/dev
* 删除：Git branch -d dev
* 删除远程分支：Git push origin -- delete dev
* 切换：Git checkout dev
* 合并分支到当前分支：Git  merge dev
* 将本地分支与远程分支绑定： Git branch -set-upstream dev origin/dev
* 推送分支到远程： Git  push origin dev



### Stash

* 将工作区修改隐藏：Git stash
* 查看隐藏列表： Git stash list
* 恢复隐藏：Git stash apply
* 删除隐藏备份： Git stash drop
* 恢复并删除隐藏备份： Git stash pop

