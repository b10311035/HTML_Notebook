# Git_Bash 學習筆記

### Git commit 和 Git push 的差異
- git作為支持分佈式版本管理的工具，它管理的庫(repository)分為本地庫、遠程庫。
- git commit 操作的是本地庫，git push 操作的是遠程庫。
- git commit是將本地修改過的文件提交到本地庫中。
- git push是將本地庫中的最新信息發送給遠程庫。

### Git 指令紀錄
1. Clone the project to a local folder：<br>
git clone https: xxxxxx
2. 看目前專案狀況：<br>
git status
3. Commit 檔案：<br>
git commit –am "Message 增加註解"
4. 檔案丟到github雲端：<br>
git push 
5. 第一次push使用不會成功，終端機沒有輸入Email、yourname，輸入以下指令：<br>
git config –global user.email "xxxxxx"<br>
git config –global user.name "xxxxxx"<br>
6. 把檔案加入git 當地資料庫：<br>
git add xxx.xxx 


### Bash 指令紀錄
1. 顯示該位置的所有隱藏和非隱藏檔案和資料夾：<br>
ls -al 
2. 在該目錄建立檔案：<br>
touch xxxx.xxx

<hr>

### 參考網址
1. [學習 MarkDown](http://xianbai.me/learn-md/article/about/readme.html)<br>