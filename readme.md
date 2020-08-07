#readme
+项目说明文档
1. 一般会随着项目放在一起
2.作为项目的说明文档

## git init
1. 把当前目录初始化为版本库
2. 当前目录会生成一个隐藏文件.git

## git add 文件名
1.把当前目录下的某个文件提交到暂存区
2.git add readme.md 把这个文件提交到暂存区
3.git add . 把当前目录所有变动提交到暂存区

## git status
查看当前目录的状态(新增，删除，修改)
## git commit -m '提交注释'
1.把暂存区的内容提交到本地仓库

## 本地仓库的三个组成部分
1.工作区（实际持有文件）（III创建文件夹里边的内容）
2.暂存区
3.本地仓库

## git log
1.查看操作日志
## git reflog
1. 查看操作日志（简单版）
## git diff 文件名
1.查看文件变更信息
## git reset --hard 版本号
1.版本回退 HEAD^回退到上一个版本，上几就加几个^
2.版本回退到指定版本 
## 主要的几个操作
1. git init ->创建版本库
2. git add 文件名 提交到暂存区
3. git commit -m '注释' 提交到本地仓库

## 远程仓库

## git remote add origin 仓库地址
1.把本地仓库和远程仓库关联

## git remote -v
1.查看本地仓库关联的远程仓库的地址

## git push -u origin master
1.git push 本地仓库提交到远程仓库
2. -u origin master  设置好默认的远程仓库和分支
3.执行完这个命令之后可以直接‘Git push’ 提交到远程仓库的master分支
4. u 是 upstream 
## 更新代码
## git pull
把远程代码更新的到本地时，一定要先提交再更新的习惯
## git branch


## test2 分支的修改

