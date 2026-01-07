# MD 轉 PDF 範例

這是一個使用 VS Code 擴充套件 **Markdown PDF（yzane.markdown-pdf）**，將 Markdown 文件輸出成 PDF 的範例專案。  
已內建固定頁首（LOGO + 公司名稱）與排版樣式，適合用來做開發文件 / 報告模板。

---

## 專案結構

- `template.md`：文件範本（Markdown 原稿）
- `output/`：PDF 輸出資料夾（匯出後的檔案放這裡）
- `.vscode/settings.json`：Markdown PDF 的輸出設定（頁面尺寸、頁首/頁尾、邊界等）
- `style/pdf.css`：PDF 的樣式（字體、表格、固定頁首等）
- `assets/`：圖片資源（例如 LOGO）

---

## 使用方式

### 1) 安裝 VS Code 擴充套件

在 VS Code Extensions 搜尋並安裝：

- **Markdown PDF**（作者：yzane）[點擊安裝](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)

---

### 2) 開啟範本並輸出 PDF

1. 打開 `template.md`
2. 於編輯器中 **右鍵**
3. 選擇：`Markdown PDF: Export (pdf)`

---

### 3) 確認輸出位置

匯出的 PDF 會放在：

- `output/`

如果你想改輸出檔名或路徑，請到：

- `.vscode/settings.json`

---

## 自訂樣式

### 調整 PDF 版面 / 匯出設定

設定檔位置：

- `.vscode/settings.json`

常見可調項目：
- 邊界（margin）
- header / footer（頁首頁尾）
- 是否顯示頁碼
- PDF 格式（A4 等）

---

### 調整 CSS 排版

CSS 檔案位置：

- `style/pdf.css`

你可以在這裡調整：
- 字體大小、行距
- H1/H2/H3 樣式
- 表格樣式
- 固定頁首（LOGO + 公司名）樣式

---