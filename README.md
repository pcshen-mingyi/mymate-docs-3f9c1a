# mymate-docs

MYmate 專案的內部文件站，用 GitHub Pages 提供固定網址給團隊成員瀏覽。

## 網址

- 首頁（文件索引）：https://pcshen-mingyi.github.io/mymate-docs-3f9c1a/
- 團隊責任定位 v2.0：https://pcshen-mingyi.github.io/mymate-docs-3f9c1a/team-roles/

## 重要：這是公開網址

GitHub Pages 的網站一律公開，**任何取得網址的人都能開啟**，不需要 GitHub 帳號。

本站採取的緩解措施：

1. repo 名稱含隨機字串，網址不易被猜到
2. 每一頁都有 `<meta name="robots" content="noindex, nofollow, ...">`，阻擋搜尋引擎收錄
3. `<meta name="referrer" content="no-referrer">`，避免點外連時把本站網址洩漏給第三方

**限制**：以上只擋搜尋引擎，擋不住拿到連結的人。請勿在此放置個資、財務資料或不能外流的機敏內容。

## 新增文件的做法

1. 在 repo 根目錄開一個資料夾，放 `index.html`（網址即 `/<資料夾名>/`）
2. **在 `<head>` 加上 noindex 三行**（從 `team-roles/index.html` 複製）——來源檔通常沒有，必須手動補
3. 在根目錄 `index.html` 加一張 card 連過去
4. `git add . && git commit && git push`，約 1 分鐘後生效

## 檔案來源

`team-roles/index.html` 來自：

```
PC Assitant/01_進行中/[PSF] MYmate(NPO Agent)/02_產出/01_願景與架構圖/MYmate_團隊責任定位_v2.0.html
```

事實來源仍是該原始檔；本 repo 為發佈用的副本（僅多加 noindex meta）。更新時重新複製並補上 meta 標籤。
