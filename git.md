# GIT常用命令

## 基本指令
git init ：初始化本地仓库

git add (file)：添加文件到**暂存区** （添加整个文件夹用-.）

git commit -m (描述) ：提交，添加到**本地仓库**  

**先git add再git commit ，这两个指令可以用 git commit -a 代替**

git commit --amend ： 取消上一次的提交记录，可以修改'描述'

git clone '远程仓库' '重命名为新的仓库' ：远程克隆

git status ：查看状态  可选参数 -s（简短状态）

git diff：查看差异

git log：查看日志  --pretty=oneline 简短日志





## 分支
 
- git branch ：创建分支或查看分支  （初始化仓库之后提交才会创建master分支）
- git branch -d (branchname) ： 删除分支
- git checkout (branchname) : 切换分支
- git merge ： 合并分支

## 远程

- git remote add origin (github网址)  
- git push -u origin master ：将主分支推送到github

