# Threads Video Downloader

一個用於下載 Threads 影片的 Android 應用程式

## 功能特點

- ✅ 內建 WebView 瀏覽 Threads
- ✅ 自動偵測頁面中的影片
- ✅ 顯示影片作者和內容預覽
- ✅ 支援批量下載
- ✅ 全選/取消全選功能
- ✅ 自動命名包含作者名稱

## 系統需求

- Android 7.0+ (API 24+)
- 網路連接
- 儲存權限（Android 9 及以下版本）

## 安裝方式

1. Clone 此儲存庫
```bash
git clone https://github.com/YenHsinCHEN/threads-downloader-app.git

專案結構
app/
├── src/main/
│   ├── java/com/example/threadsdownloader/
│   │   └── MainActivity.kt
│   ├── res/
│   │   ├── layout/
│   │   │   ├── activity_main.xml
│   │   │   ├── dialog_video_selector.xml
│   │   │   └── item_video.xml
│   │   └── drawable/
│   └── AndroidManifest.xml

### 2. **添加 .gitignore 確保正確**

確認你的 `.gitignore` 包含：
```gitignore
*.iml
.gradle
/local.properties
/.idea
.DS_Store
/build
/captures
.externalNativeBuild
.cxx
*.apk
*.aab
*.jks
*.keystore

3. 提交 README 到 GitHub
# 添加 README
git add README.md

# 提交
git commit -m "Add README documentation"

# 推送
git push

🔄 日常工作流程
每次修改程式碼的標準流程：
# 1. 開始工作前，確保是最新版本
git pull

# 2. 修改你的程式碼...

# 3. 查看改了什麼
git status

# 4. 添加所有修改
git add .

# 5. 提交（寫清楚的訊息）
git commit -m "具體說明修改內容"

# 6. 推送到 GitHub
git push
