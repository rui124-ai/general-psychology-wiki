\# AGENTS.md - 普通心理學知識庫 (General Psychology Wiki) 開發指南 
## 1\. 專案目的 (Project Purpose) 本專案旨在建立一個結構化、高可讀性且易於擴充的「普通心理學學習與知識庫網站 (General Psychology Wiki)」。 用以系統化整理心理學核心概念（如認知、記憶、情緒、動機等），方便大一學生進行課後複習與知識檢索。 
## 2\. 網頁整體風格與設計規範 (Design System) 所有頁面必須保持一致的視覺風格與良好閱讀體驗： 
- \*\*色調主題\*\*：採用心理學典雅專業色調（主色：#3A6D8C 經典藍；輔助色：#6A9AB0 柔和藍；背景：#F9F9F9 近純白；卡片背景：#FFFFFF）。
- - \*\*字體設定\*\*：標準繁體中文系統字型（Line-height: 1.65，字體大小 16px，確保長時間閱讀不費力）。
  - - \*\*UI 元件\*\*： - 頂部導覽列 (Navbar)：包含網站名稱與主要章節連結。
  - - 卡片區塊 (Cards)：重點概念需使用圓角（border-radius: 10px）與輕微陰影（box-shadow: 0 4px 6px rgba(0,0,0,0.05)）。
  - - 專有名詞標籤 (Badge)：心理學專有名詞（如 \`Cognition\`, \`Memory\`）需使用小標籤凸顯。
  ## 3\. 檔案結構與命名規範 (File Structure &amp; Naming) 新增或修改檔案時，必須嚴格遵守以下目錄結構與命名邏輯： \`\`\`text / ├── index.html # 網站首頁（總覽與導覽） ├── AGENTS.md # AI 開發規則指南 ├── assets/ │ ├── css/style.css # 全域統一樣式表 │ └── images/ # 示意圖與圖表資料夾 └── pages/ # 心理學主題內容頁面 ├── cognition-memory.html # 認知與記憶篇 └── emotion-motivation.html 
# 情緒與動機篇
