# 怎么去用git进行版本控制

## 1.git init
## 2.一些git的命令
`git add.`  //将代码放入暂存区，stage  
`git commit -m "......."`  //将暂存区代码提交至本地仓库  
`git log`  
`git status`  
`git reset --hard HEAD^`  
`git diff`  

## git的一些基本概念
    commit
    branch
    checkout
    pull
    push
    clone
    

## 上传至GitHub
### 1.先去建一个repositories
### 2.关联仓库地址
`git remote add origin +仓库地址`  
### 3.第一次上传
`git push -u origin main https://github.com/ JavonRong/git_markdown`  
或 `git push -u origin master https://github.com/JavonRong/git_markdown`   

###之后每一次上传到GitHub 仅需以下代码：
`git add .`  
`git commit -m "版本说明"`  
`git push`  
