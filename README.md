# Git

## git

```bash
# 查詢git版本
git -v

# 查詢設定
git config --list

# 設定名稱
git config --global user.name 你的名字

# 設定Email
git config --global user.email 你的email


# git初始化
git init

# 查看git 狀態
git status

# 將所有檔案加入暫存區
git add .

# 提交版本
git commit -m "訊息"

# 查看版本
git log
git log --online
git reflog


# 回復版本
git reset 版本號 --hard

# 建立遠端連線
git remote add origin 連線位置

# 推送至遠端
git push origin master

# 推送至遠端並將目前連線與分支設定為預設串流
git push origin master -u

# 若有設定預設串流的推送
git push


```