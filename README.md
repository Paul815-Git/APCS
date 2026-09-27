# APCS 指南與 Colab 自學課程

網站保留 APCS 考試與升學資料（36 所大學、62 筆招生組別），Python 課程改用 Google Colab 筆記本。

## 更新你的 GitHub 網站

1. 解壓縮 `apcs-colab-lesson01.zip`。
2. 開啟 https://github.com/Paul815-Git/APCS ，選 **Add file → Upload files**。
3. 上傳解壓縮後的全部五個檔案，放在 `main` 分支最外層；更新同名檔案並提交變更。不要上傳 ZIP，也不要多包一層資料夾。
4. 沿用現有 Pages 設定，等待部署完成。
5. 開啟 https://paul815-git.github.io/APCS/ ，點「Colab 自學：開始 Python 第 1 課」。

本次檔案：

```text
index.html        原指南，加入 Colab 課程入口
lesson-01.html    第 1 課介紹、Colab 直達與匯入說明
lesson-01.ipynb   學生教材：說明、範例、空白練習、提示與自我檢核
README.md        本說明
.nojekyll        GitHub Pages 靜態檔案設定
```

新課程不載入舊版 `lesson.js`、`lesson.css`、`lesson-worker.js` 或 `lesson-rules.js`。如果曾上傳過舊檔，留著不影響新課程。舊版瀏覽器學習紀錄不會匯入 Colab。

## 第 1 課直達連結

https://colab.research.google.com/github/Paul815-Git/APCS/blob/main/lesson-01.ipynb

**必須先把本次 `lesson-01.ipynb` 上傳至 main 分支，這個連結才有教材可開啟。** 本壓縮檔不會自動上傳或發布。

在上傳前也能試用：開啟 https://colab.research.google.com/?hl=zh-tw ，選 **檔案 → 上傳筆記本**，匯入 `lesson-01.ipynb`。

## 學生使用流程

1. 登入 Google 帳號，開啟教材。
2. 選 **檔案 → 在雲端硬碟中儲存副本**，確認已存進自己的 Google Drive，改名為 `第1課_暱稱`。
3. 先讀說明、寫預測，再逐格執行。不要從「全部執行」開始。
4. 完成空白練習、除錯紀錄與三行介紹卡。自我檢核是手動確認，沒有自動批改或後台成績紀錄。
5. 確認已保存，依老師要求分享自己的副本。分享前確認老師有檢視權限。

程式在 Colab 的雲端環境執行，需要網路。筆記本可以保存，但運算環境可能中斷或重建；後續教變數時需從上往下重新執行。手機可開始短練習，之後在電腦上開啟同一份副本接續。

## 老師試教重點

- 第一次使用 Colab 預留約 30–40 分鐘；熟悉介面後約 20 分鐘。
- 本課只需 Python 3，不需安裝套件、掛載 Drive 或使用 GPU。
- 修錯題為刻意缺引號的程式。預設以 `#` 註解，學生依題意移除 `#` 後，會看到預期的 SyntaxError，再修正。請勿將這個教學錯誤誤認為教材損壞。
- 請學生現場換一組文字重新寫，判斷能否獨立完成，而不只看輸出。
- 第 2 課以後尚未製作；目前僅交付第 1 課。

## 驗證與來源

筆記本已通過 nbformat 格式驗證、Python 3 本地核心逐格執行，以及五個練習參考解的輸出檢查。發布的學生版保留空白作答區，清除輸出以避免提前揭露預測答案。未代替學生登入 Google 帳號測試雲端保存或分享。

- [Google Colab 官方 FAQ](https://research.google.com/colaboratory/faq.html)
- [Google 官方 GitHub 筆記本開啟示例](https://colab.research.google.com/github/googlecolab/colabtools/blob/main/notebooks/colab-github-demo.ipynb)
- [GitHub Pages 發布設定](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

原 APCS 資料整理日期：2026-09-27。各校門檻不等於錄取分數，來源與限制仍保留在原指南。
