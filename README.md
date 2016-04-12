# DemoForGitTest
demo for  git commend

###1. 拉代码到本地

  git clone 远程仓库地址 本地目录
  
  例如：
  
  git clone https://github.com/zl280513013/DemoForGitTest.git
  
###2. 本地修改代码

  按照产片的需求，写代码，修改代码，添加代码等
  
  git add 文件路径
  
  git commit -m "提交的commit信息"
  
  例如：
  
  新建一个demo.txt
  
  vi demo.txt
  
  
  把demo.txt纳入版本管理
  
  git add demo.txt
  
  
  把demo.txt提交到本地代码仓库
  
  git commit -m "提交代码"
  
###3. 将本地的修改提交到远程仓库

  git pull  从服务端的仓库取下最新的代码并月本地的进行merge
  
  git push  把本地的已经commit过的代码提交的远程仓库
  
  
  例如：
  
  git pull --rebase
  
  git push

