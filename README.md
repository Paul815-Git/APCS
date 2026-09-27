# APCS：HTML 講義＋Colab 作業本

學生在自己的網站看範例、解說及提示，再到 Colab 完成指定題目，分享副本給老師。第 1、2 課已改成這個模式。

## 上傳更新

1. 解壓縮 `apcs-html-handouts-colab-homework.zip`。
2. 開啟 https://github.com/Paul815-Git/APCS ，選 **Add file → Upload files**。
3. 把解壓縮後的 **9 個檔案全部上傳**至 main 分支最外層，更新同名檔案並提交。不要上傳 ZIP 或多包一層資料夾。
4. 等既有 GitHub Pages 部署完成。

```text
index.html       原 APCS 指南，內容保留
courses.html     課程目錄，以「閱讀講義」為主要入口
lesson-01.html   第 1 課完整講義
lesson-02.html   第 2 課完整講義
teaching.css     講義與目錄樣式（必須一起上傳）
lesson-01.ipynb  第 1 課精簡作業本
lesson-02.ipynb  第 2 課精簡作業本
README.md        本說明
.nojekyll        GitHub Pages 設定
```

## 給學生的入口

- 課程目錄：https://paul815-git.github.io/APCS/courses.html
- 第 1 課講義：https://paul815-git.github.io/APCS/lesson-01.html
- 第 2 課講義：https://paul815-git.github.io/APCS/lesson-02.html

先讀講義，再按「開啟 Colab 作業本」。每道題目用 A–E 對照，Colab 題目亦有返回講義的提示連結。範例結果和解題提示在 HTML 預設收合。HTML 不執行 Python、不儲存作答或記錄成績。

## Colab 現在只放作業

第 1 課 12 個區塊、第 2 課 14 個區塊：簡短開始說明、A–E 題、作答區、必要的觀察紀錄與交作業說明。目錄預設收起；介面是否沿用個人設定仍由 Colab 決定。完整講義與範例解說均移到 HTML。

學生第一次開啟後先「在雲端硬碟中儲存副本」，改名為「第幾課_暱稱」。一堂課只要保存一次，後續切回同一份副本作答，避免每道題都另存新副本。完成後保留程式與輸出，分享自己的副本给老師並確認老師有查看權限。

老師更新 GitHub 原始作業本，不會修改學生已保存的副本；也不會自動搬移學生舊版的作答。做過舊版的學生可以保留舊副本。要換新版則另存新副本，再自行搬移需要的程式。

Colab 直達連結需先上傳新版 ipynb 才會讀到新內容。尚未上傳時，可以在 Colab 用「檔案 → 上傳筆記本」匯入本地檔案。

## 教師備註

第 1 課 D 題刻意缺引號，預設用 # 註解。學生先移除 # 觀察 SyntaxError，再修正。第 2 課 D 題刻意使用兩個程式區，實驗「編輯」與「執行」不同；E 題保留購物單第二次修改後的結果。

目前採手動自我檢核與老師查看，沒有自動批改、收件系統或後端運算。Colab 執行需要網路。第 3 課尚未開放。

筆記本已用本地 Python 核心執行檢查，學生交付版保留未填答案與空輸出。未代登入學生帳號測試保存及分享。

[Google Colab 官方 FAQ](https://research.google.com/colaboratory/faq.html)
