# git 命令
1. git init &nbsp; git 对文件没有管理权限，所以需要 git init 使 git 可以管理该文件
2. git status &nbsp; 获取该分支的状态
3. git add 文件名 &nbsp; 将修改的文件提交到暂存区，这样 git 可以追踪到文件的修改
4. git rm --cached 文件名 &nbsp; 将修改的文件从暂存区删除 本地文件不会发生变化
5. git commit -m "提交信息" 文件名 &nbsp; 将暂存区的文件提交到本地仓库
6. git reflog &nbsp; 查看该分支下的版本信息 ( HEAD 指针指向哪个 当前版本就是哪个版本)
7. git log &nbsp; 查看该分支下版本的详细信息
8. git reset --hard 版本号 &nbsp; 切换版本到该版本号对应的版本 ( 版本切换原理: 实际上底层只是修改 HEAD 指针的指向，HEAD 指向 分支，分支指向版本，从而实现版本切换 )
9. git branch -v &nbsp; 查看当前项目的分支
10. git branch 分支名 &nbsp; 创建新分支，新分支内容与当前分支一致
11. git checkout 分支名 &nbsp; 切换分支
12. git merge 分支名 &nbsp; 把指定分支合并到当前分支上
13. git remote -v 查看当前所有远程地址别名
14. git remote add 别名 远程地址 创建别名
15. git push 别名 分支 将本地库代码提交到远程库中(最小单位为分支)
16. git pull 别名 分支 拉取远程库到本地库

git底层原理：
  head指针指向分支，分支指向版本

# linux 命令
1. ll &nbsp; 查看该文件下的文件
2. ll -a &nbsp; 查看该文件下的所有文件( 包含隐藏的文件 )
3. cd 文件名/路径 &nbsp; 进入某一文件
4. vim 文件名 &nbsp; 创建/进入该文件进行编辑等操作
5. cat 文件名 &nbsp; 查看该文件内容
6. tail -n 1 文件名 &nbsp; 查看该文件最后一行内容

# vim 命令
1. Enter &nbsp; 进入编辑模式
2. Esc &nbsp; 进入操作模式
3. yy &nbsp; 操作模式中复制该行
4. p &nbsp; 操作模式中粘贴复制的内容
5. :wq &nbsp; 操作模式中保存该文件
