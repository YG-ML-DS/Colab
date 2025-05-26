# Py-Colab
## sync from git to local 
> github command

***初始阶段： clone folder***

cd /Users/yun/Documents/git_local

git clone https://github.com/YG-ML-DS/Py-Colab.git colab

***后续更新***

cd /Users/yun/Documents/git_local/colab

git pull origin main

# the other way 
## sync from local to git 
> 初始阶段： 先建立 git repository 下面开始 upload

cd /Users/yun/Documents/git_local/ML

git init

git add . 

git commit -m”initial” 

git remote add origin https://github.com/YG-ML-DS/ML-Py.git 

git push -u origin main

** in case sometimes it is not “main”, it is “master” — change to “main” 

git branch -m master main



> 后续更新

cd /Users/yun/Documents/git_local/_list

git status 

git add .

git commit -m””

git push origin main  
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE0MzI4MzQzOTRdfQ==
-->