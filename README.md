# NEJM-style Academic Paper LaTeX Template (XeLaTeX, Chinese Support)

本專案提供一份符合 NEJM 論文格式的 LaTeX 模板，支援 XeLaTeX 編譯與中英文混排，適用於 original article、case report、medical image 多種論文型態。

## 編譯方式
建議使用 XeLaTeX 編譯，並安裝必要的套件（如 fontspec、xeCJK、geometry、biblatex 等）。

## 結構
- `main.tex`：主檔案，可彈性 include 各種論文型態子檔案。
- `sections/`：各論文型態內容。
- `refs.bib`：BibTeX 參考文獻檔案。

## 參考文獻
預設使用 biblatex，風格近似 NEJM。

## 子檔案彈性設計
可於 `main.tex` 中指定 include 哪一種論文型態內容。
