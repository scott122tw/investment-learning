# 投資學習計畫網站

這是一個基於數據分析的投資學習計畫網站，展示如何透過歷史數據建立投資框架。

## 📁 專案結構

```
學習計畫網頁/
├── index.html                          # 首頁（投資學習計畫主頁）
├── 實戰範例_利率轉折分析.html           # 實戰分析範例頁
├── images/                             # 圖片目錄
│   ├── 利率路徑與轉折點_20251130_193701.png
│   └── 每次事件報酬熱力圖_20251130_193701.png
├── 利率轉折分析結果_20251130_193659.csv # 分析數據
└── README.md                           # 本說明檔案
```

## 🚀 部署到 GitHub Pages

### 步驟 1：建立 GitHub Repository

1. 前往 [GitHub](https://github.com) 並登入
2. 點擊右上角的 `+` → 選擇 `New repository`
3. 填寫專案資訊：
   - **Repository name**: `investment-learning`（或您喜歡的名稱）
   - **Description**: 投資學習計畫網站
   - 選擇 `Public`（公開才能使用免費的 GitHub Pages）
   - 不勾選 "Add a README file"
4. 點擊 `Create repository`

### 步驟 2：上傳檔案到 GitHub

在終端機中執行以下指令：

```bash
# 進入專案目錄
cd "/Users/scott/Library/Mobile Documents/com~apple~CloudDocs/測試/學習計畫網頁"

# 初始化 Git（如果尚未初始化）
git init

# 將所有檔案加入版本控制
git add .

# 提交變更
git commit -m "Initial commit: 投資學習計畫網站"

# 連結到你的 GitHub repository（請替換為你的 username 和 repo name）
git remote add origin https://github.com/YOUR_USERNAME/investment-learning.git

# 推送到 GitHub
git branch -M main
git push -u origin main
```

**注意**：請將 `YOUR_USERNAME` 替換為您的 GitHub 使用者名稱。

### 步驟 3：啟用 GitHub Pages

1. 在 GitHub repository 頁面，點擊 `Settings`（設定）
2. 左側選單選擇 `Pages`
3. 在 **Source** 區域：
   - Branch: 選擇 `main`
   - Folder: 選擇 `/ (root)`
4. 點擊 `Save`（儲存）

等待約 1-2 分鐘後，您的網站就會上線！

### 步驟 4：訪問您的網站

網址格式為：
```
https://YOUR_USERNAME.github.io/investment-learning/
```

## 📊 上傳圖片檔案

請將以下圖片檔案放入 `images/` 目錄：

- `利率路徑與轉折點_20251130_193701.png`
- `每次事件報酬熱力圖_20251130_193701.png`

如果圖片尚未上傳，網頁會顯示提示訊息。

## 🔄 更新網站內容

每次修改檔案後，執行以下指令更新：

```bash
git add .
git commit -m "描述你的更改"
git push
```

## 📱 響應式設計

網站已針對不同裝置螢幕大小進行優化，在手機、平板和電腦上都能良好顯示。

## 🎨 頁面說明

### 首頁 (index.html)
- 投資學習計畫的完整介紹
- CAFE 循環框架說明
- 測試範例概覽
- 導航連結到實戰範例頁

### 實戰範例頁 (實戰範例_利率轉折分析.html)
- 利率轉折點分析的詳細說明
- 四步驟框架實作
- 數據分析結果與視覺化
- 程式碼範例

## 📞 技術支援

如有任何問題或建議，請透過 GitHub Issues 回報。

## 📄 授權

本專案僅供學習參考使用。
