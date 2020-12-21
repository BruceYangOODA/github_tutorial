# github_tutorial

### 莫烦Python
Git 版本管理 (教学 教程 tutorial) [Youtube](https://www.youtube.com/watch?v=kQSzft2Jj8Y&list=PLXO45tsB95cKysjmSNln65YoUt9lwEl7-&ab_channel=%E8%8E%AB%E7%83%A6Python)

[Git 官方工具](https://git-scm.com/downloads)

[Git工具 安裝說明](https://mofanpy.com/tutorials/others/git/)

cd ~/desktop  
cd ~/OneDrive/桌面/gitTUT  
git config --global user.name "Zeros"  
git config --global user.email "by@email.com"  
git config user.name  
git init  初始化文件庫管理  
touch hellow.py  建立文件  
git add hellow.py  將文件加入git管理庫  
git status  查看git管理狀態  
git status -s  查看git管理狀態  
git log  查看修改紀錄  

打開 hellow.py 修改內容  
git add hellow.py  將修改內容加入git管理庫  
git commit -m "change_1"  修訂版本 "change_1" 建立修改時間點
git diff  查看版本差異  
git diff --cached  

git add .  所有文件的修改

git log --oneline  修訂版本一覽  

git commit --amend --no-edit  
git reset hellow.py 提交的staged 返回 modified狀態  

git reset --hard HEAD  回到上一個修訂版本  
git reset --hard HEAD^^  回到上兩個修訂版本 
git reset --hard HEAD~100  回到一百個前的修訂版本 
git reset --hard ID號碼  回到ID號碼的修訂版本  

git reflog  查看修訂版本變更版本的狀態  

git checkout ID號碼 -- hellow.py  把文件回復到ID號碼的修訂版本  

git log --oneline  --graph  查看分支狀態  
git branch 分支名稱  建立分支  
git branch  瀏覽分支 
git checkout 分支名稱  移動到分支  
git checkout -b 分支名稱  建立分支並移動到分支  

git merge --no-ff -m "abcde" 分支名稱  把分支合併到master  

git stash  暫存目前工作，可以執行其他分支作業   
git checkout 分支名稱  回到暫存工作的分支
git stash pop  讀取暫存工作，繼續此分支作業  

git remote add origin "git hub url"  
git push -u origin master  把本地端文件管理庫上傳  
git push -u origin 分支名稱  把本地端分支文件上傳  

-----
git commit --allow-empty -m "first commit"  





