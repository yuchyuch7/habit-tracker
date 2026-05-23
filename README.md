# 習慣追蹤 App

一個輕量的 PWA 健康習慣追蹤工具，可以加入手機主畫面當 App 使用。

## 功能
- 新增打勾型或計數型習慣
- 日 / 週 / 月 / 年 四種瀏覽模式
- 連續天數（Streak）追蹤
- 統計儀表板
- 資料存在本機（localStorage）

## 部署步驟

### 1. 建立 GitHub Repo
去 github.com 新增一個 public repo（例如 `habit-tracker`）

### 2. 上傳檔案
```bash
cd habit-tracker
git init
git add .
git commit -m "init"
git remote add origin https://github.com/你的帳號/habit-tracker.git
git push -u origin main
```

### 3. 開啟 GitHub Pages
1. 進入 repo → Settings → Pages
2. Source 選「GitHub Actions」
3. 等待部署完成，網址會是 `https://你的帳號.github.io/habit-tracker/`

### 4. 手機加入主畫面
用 Safari（iOS）或 Chrome（Android）開啟網址
- iOS：點右下角分享 → 「加入主畫面」
- Android：點右上角選單 → 「新增到主畫面」

## 注意
需要自行準備圖示檔案 `icon-192.png` 和 `icon-512.png` 放在根目錄，
不然加入主畫面時不會有 App 圖示（不影響功能）。
