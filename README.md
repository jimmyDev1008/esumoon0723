# Esumoon 易善美 — 純鈦茶器品牌官網（靜態重建版）

以乾淨的 HTML / CSS / 原生 JavaScript 重建的多頁靜態網站，內容取材自原 Wix 網站
（<https://h09410692.wixsite.com/my-site-3>）。**不含電商後端**，純品牌展示用途。

## 頁面

| 檔案 | 內容 |
| --- | --- |
| `index.html` | 主頁：品牌核心價值、純鈦特性、系列精選、影像廊 |
| `about.html` | 關於我們：品牌故事、博友製鈦台灣總代理 |
| `titanium.html` | 純鈦優勢：材質特性、光觸媒、真空千度重結晶工藝 |
| `products.html` | 所有產品：提梁壺系列 + 茶席配件 + 作品實拍 |
| `reports.html` | 檢測報告：國際設計獎、食品安全認證、博友製鈦大事記 |
| `faq.html` | 常見問題：手風琴式 12 則問答 |
| `contact.html` | 聯絡我們：表單（僅前端）與聯絡資訊 |

## 目錄結構

```
esumoon/
├── *.html                 # 7 個頁面
├── css/style.css          # 設計系統（配色、字型、元件、RWD）
├── js/main.js             # 行動選單、FAQ 手風琴、捲動進場、表單提示
├── assets/images/
│   ├── site/              # hero、品牌 logo、獎項標誌
│   └── products/          # 產品實拍（取自原站）
└── README.md
```

## 本地預覽

直接以瀏覽器開啟 `index.html` 即可；或啟動簡易伺服器：

```bash
# Python
python -m http.server 8000
# 然後開啟 http://localhost:8000
```

## 設計

- 字型：Noto Serif TC（標題）+ Noto Sans TC（內文），透過 Google Fonts 載入
- 配色：米白 `#fbf8f2`、炭黑 `#23201b`、金 `#b08d4f`
- 響應式：桌機 / 平板 / 手機三段式斷點

## 待辦 / 可延伸

- 聯絡表單目前僅前端提示，未串接寄送服務（可接 Formspree、EmailJS 或自建後端）
- 產品照片為系列代表圖，非逐一對應每個 SKU；如需完整商品可再逐項補齊
- 社群連結（Facebook / Instagram）目前為 `#`，待填入實際網址
- 可視需求補上英文 / 簡體版本（原站有 en / zh-cn）

## 資料來源說明

文字內容、產品名稱與圖片素材均取自原 Wix 網站，供品牌自有網站重建之用。
聯絡資訊已更新為實際資料（Email：Hannah@esumoon.net｜高雄市），
原站頁尾的 Wix 範本預設值（info@mysite.com、123-456-7890）已移除。
