# 桌遊機制索引

依 Geoffrey Engelstein 與 Isaac Shalev《Building Blocks of Tabletop Game Design: An Encyclopedia of Mechanisms》第二版（CRC Press, 2022）整理的桌遊機制索引，收錄 13 章、203 個機制；每個機制附循環示意動畫、說明、設計考量、代表遊戲與相關機制，另有各章導讀與全書架構圖。

整個網站只有一個檔案 `index.html`，樣式、資料與動畫都包在裡面，只有字型從 Google Fonts 載入。

## 部署到 GitHub Pages

1. 在 GitHub 建立新的 repository，例如 `boardgame-mechanisms`；免費帳號需要設為 Public。
2. 在 repository 頁面點 **Add file → Upload files**，上傳 `index.html` 與這份 `README.md`，再按 **Commit changes**。
3. 到 **Settings → Pages**，在「Build and deployment」把 **Source** 設為 **Deploy from a branch**，分支選 `main`、資料夾選 `/ (root)`，按 **Save**。
4. 等一兩分鐘，同一頁上方會出現網址，格式是 `https://帳號.github.io/repository名稱/`。

## 更新

用新版的 `index.html` 覆蓋舊檔並 commit，GitHub Pages 會自動重新部署。

## 直接連到某一頁

網址後面加上 `#` 就能直接開啟特定頁面，方便上課時分享：

- 單一機制：`#TRN-04`（漸進式回合順序）
- 各章導讀：`#CH1` 到 `#CH13`
- 全書架構圖：`#MAP`

## 關於內容

機制名稱、編號、章節與頁碼依原書第二版目次；中文名稱、說明、設計考量與代表遊戲是本索引自行撰寫的摘要，不含原書文字，細節請以原書為準。本索引與原書作者、出版社無關，遊戲名稱屬於各自的權利人。
