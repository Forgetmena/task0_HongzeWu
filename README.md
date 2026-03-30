# Task0 Report
## 个人基本信息
**1，姓名：** 伍竑泽  
**2，学号：** 2025211***  
**3，学院：** 计算机学院  
## 对git和github的理解
### 关于git  
#### git init：用于将当前目录转化为git可管理的本地仓库，但不会追踪任何文件
**使用方法：**  
1,`git init -b main` 初始化并设置默认分支为main  
2,`git init`
#### 添加README.md
**使用方法：**  
`echo "# Project Description" > README.md`
#### git add：将工作区的文件放入暂存区
**使用方法：**  
1，`git add README.md` 精准添加目标文件  
2，`git add .` 添加当前目录所有变更（含子目录）  
3，`git add -A` 添加所有变更（含删除操作）  
4，`git reset HEAD README.md` 取消暂存，文件内容保留
#### git commit：将暂存区的变更永久保存到本地Git仓库 
**使用方法：**  
1，`git commit -m "提交名称"`  
2，`git log` 查看提交记录
#### git push：将本地仓库已提交的变更同步至远程仓库
**使用方法**  
1，`git push -u origin main` 首次推送  

>origin：远程仓库别名  
>main：本地分支名  
>-u：首次推送时绑定上下游

2，`git push` 后续推送  
3，`git remote add origin <仓库的URL>`  
4，`git -v remote` 验证
### 关于GitHub
