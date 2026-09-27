# APCS 程式設計檢測準備指南

可直接使用 GitHub Pages 發布的靜態網站，不需要安裝套件或執行建置。

包含 APCS 介紹、考科與級分試算、8 週準備計畫、練習資源，以及 116 學年度官方採計表全部 36 所大學、62 筆招生組別（APCS 組 49 筆、資安組 13 筆）。支援校系搜尋、組別與門檻篩選。

## 用 GitHub 網頁上傳並發布

1. 解壓縮 `apcs-github-pages.zip`。
2. 登入 GitHub，建立新的儲存庫（New repository），名稱可填 `apcs-guide`，選擇 **Public**。可勾選新增 README，方便看到上傳選單。
3. 在儲存庫的 **Code** 頁面，選 **Add file → Upload files**。若是空白儲存庫，點 **uploading an existing file**。
4. 上傳解壓縮後的 `index.html`、`README.md`、`.nojekyll`，按 **Commit changes**。請上傳檔案本身，不要上傳 ZIP，也不要多包一層資料夾；`index.html` 必須直接出現在儲存庫最外層。若檔案選擇器未顯示 `.nojekyll`，先上傳其他兩個檔案也能發布此單頁網站。
5. 進入 **Settings → Pages**。
6. **Build and deployment → Source** 選 **Deploy from a branch**。
7. **Branch** 選 **main**，資料夾選 **/ (root)**，按 **Save**。若你的預設分支名稱不同，選實際放置 `index.html` 的分支。
8. 等待部署完成，在 Pages 設定頁開啟網站連結。以儲存庫 `apcs-guide` 為例，網址通常為 `https://你的帳號.github.io/apcs-guide/`。

若尚未出現網頁，查看儲存庫 **Actions** 的 Pages 部署是否完成；也確認發布分支和 `index.html` 的位置。日後上傳新版 `index.html` 並提交變更，GitHub Pages 會重新發布。

設定依據：[GitHub 官方 Pages 發布來源說明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)。GitHub Free 可使用公開儲存庫發布 Pages。

## 本機閱讀與資料說明

- 直接用瀏覽器開啟 `index.html` 即可預覽。
- 網頁樣式與互動程式都在 `index.html` 內；外部資料來源連結需要網路。
- 勾選進度儲存在目前瀏覽器；本機檔案與線上網站的進度不會自動同步。
- 資料整理日期為 2026-09-27。級分門檻不等於錄取分數；年度、未核實項目與來源已標示於網頁。
- [116 學年度官方 APCS 採計表](https://www.cac.edu.tw/apply116/document/116APCS_asdf_20260831.pdf)。

## 檔案

```text
index.html    網站首頁，保留完整內容與互動功能
README.md     本說明
.nojekyll     告知 GitHub Pages 直接提供靜態檔案
```
