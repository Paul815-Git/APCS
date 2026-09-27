# APCS 指南與 Python 十課自學

保留 APCS 考試與升學指南，提供 10 份 HTML 講義、10 份精簡 Colab 作業本，共 50 個練習。講義負責解說，Colab 只放題目與作答區。

## 一次部署

1. 解壓縮 `apcs-python-10-lessons.zip`。
2. 開啟 https://github.com/Paul815-Git/APCS ，選 Add file → Upload files。
3. 上傳解壓縮後的全部 26 個檔案，放在 `main` 分支最外層，更新同名檔案並提交。不要上傳 ZIP，也不要多包一層資料夾。
4. 沿用目前 GitHub Pages 設定，等待部署完成；可在 Actions 查看進度。
5. 開啟 https://paul815-git.github.io/APCS/courses.html ，確認十課與 Colab 按鈕。

若是全新儲存庫：Settings → Pages → Deploy from a branch → main → / (root) → Save。

## 檔案

- `index.html`：原 APCS 指南及校系資料，新增十課入口。
- `courses.html`：十課目錄與學習方式。
- `lesson-01.html` 到 `lesson-10.html`：講義、範例、摺疊提示。
- `lesson-01.ipynb` 到 `lesson-10.ipynb`：精簡作業本。
- `teaching.css`：手機及電腦版共用樣式。
- `teacher-guide.md`：時程、設備、收作業與回饋安排。
- `.nojekyll`：GitHub Pages 靜態檔設定。

Colab 連結固定使用 `Paul815-Git/APCS` 的 `main` 分支。若更換帳號、儲存庫或分支，需同步修改 HTML 與筆記本中的網址。

## 學生流程

在網站讀一段 → 切回自己的 Colab 副本做對應題目 → 保留程式及結果 → 分享副本給老師。舊副本不會隨 GitHub 更新而被修改。

第 1–8 課可以 Android 起步；第 9–10 課安排電腦 IDLE 與 .py 操作。網站沒有後端、自動評分或學生進度紀錄。
