# APCS 指南與 Colab 自學課程（第 1、2 課）

原 APCS 指南保留，新增課程目錄與第 2 課「讓 Python 幫你算」。學生各自保存 Colab 副本、完成練習，再分享給老師。

## 上傳到現有 GitHub

1. 解壓縮 **apcs-colab-lessons01-02.zip**。
2. 到 https://github.com/Paul815-Git/APCS ，選 **Add file → Upload files**。
3. 把解壓縮後的 **7 個檔案全部上傳**到 main 分支最外層，更新同名檔案並提交變更。不要上傳 ZIP 或多包一層資料夾。
4. 沿用現有 Pages 設定，等部署完成。

| 檔案 | 用途 |
|---|---|
| index.html | 原 APCS 指南，入口改連課程目錄 |
| courses.html | 第 1、2 課的課程目錄 |
| lesson-01.html | 第 1 課介紹，加入前往第 2 課的按鈕 |
| lesson-01.ipynb | 第 1 課，加入下一課連結 |
| lesson-02.ipynb | 第 2 課學生筆記本 |
| README.md | 本說明 |
| .nojekyll | GitHub Pages 設定 |

## 上傳後的網址

- 指南：https://paul815-git.github.io/APCS/
- 課程目錄：https://paul815-git.github.io/APCS/courses.html
- 第 2 課 Colab：https://colab.research.google.com/github/Paul815-Git/APCS/blob/main/lesson-02.ipynb

**先上傳筆記本，Colab 直達網址才有教材可讀。** 壓縮檔不會自動發布。若還沒上傳，也可到 Colab 選「檔案 → 上傳筆記本」，匯入解壓縮後的檔案。

## 第 2 課教學安排

40–50 分鐘，可拆成單元 0–3 與 4–7 兩次完成。內容包括四則運算、括號、變數、Colab 執行順序及點心購物單。含四個練習、分層提示、獨立任務與手動自我檢核；沒有自動評分或後台成績。

購物單第一次結果是 115 元／找零 85 元，改成 4 包餅乾後是 140 元／找零 60 元。學生需使用變數與算式，不能直接輸出固定答案。請老師再指定不同數量讓學生現場修改，確認能獨立操作。

學生版有空白程式練習區，範例未保留預先執行的輸出，讓學生先預測再執行。教材使用 Python 3，不需安裝套件或使用 GPU。

## 保存與交作業

學生登入自己的 Google 帳號，開啟教材後選「檔案 → 在雲端硬碟中儲存副本」，改名為「第2課_暱稱」。作答後確認已保存，點「共用／分享」給老師檢視權限，再交自己的副本網址；不要交原始 GitHub 教材網址。

運算環境可能中斷或重建。保存筆記本不代表保存變數狀態；需要時從上往下重新執行相關程式區。第 2 課已安排這個實驗。

## 驗證與來源

已完成本地 Python 核心的筆記本逐格執行、範例及練習答案、兩組購物金額與執行順序驗證。未代登入 Google 帳號驗證雲端分享。第 3 課尚未開放。

- [Colab 官方 FAQ](https://research.google.com/colaboratory/faq.html)
- [GitHub Pages 發布說明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

APCS 指南仍保留原有 36 所大學、62 筆招生組別與來源說明。舊的網頁 Python 執行引擎不再使用；已上傳的舊 JS/CSS 留著不影響本次更新。
