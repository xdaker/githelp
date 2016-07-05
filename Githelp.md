#Git 常用命令行

  [TOC]
  
##初始化
###配置使用git仓库的人员姓名  
git config --global user.name "Your Name Comes Here"  (改引号里面的)
  
###配置使用git仓库的人员email  
git config --global user.email you@yourdomain.example.com  

##取得Git仓库

###初始化一个版本仓库  
git init  
  
###Clone远程版本库  
git clone git@xbc.me:wordpress.git  
  
###添加远程版本库origin 
git remote add origin git@xbc.me:wordpress.git  
**语法为 git remote add [shortname] [url]** 
  
###查看远程仓库  
git remote -v  