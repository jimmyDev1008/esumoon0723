# Esumoon 易善美 — 纯钛茶器品牌官网（静态重建版）

以干净的 HTML / CSS / 原生 JavaScript 重建的多页静态网站，内容取材自原 Wix 网站
（<https://h09410692.wixsite.com/my-site-3>）。**不含电商后端**，纯品牌展示用途。

## 页面

| 档案 | 内容 |
| --- | --- |
| `index.html` | 主页：品牌核心价值、纯钛特性、系列精选、影像廊 |
| `about.html` | 关于我们：品牌故事、博友制钛台湾总代理 |
| `titanium.html` | 纯钛优势：材质特性、光触媒、真空千度重结晶工艺 |
| `products.html` | 所有产品：提梁壶系列 + 茶席配件 + 作品实拍 |
| `reports.html` | 检测报告：国际设计奖、食品安全认证、博友制钛大事记 |
| `faq.html` | 常见问题：手风琴式 12 则问答 |
| `contact.html` | 联络我们：表单（仅前端）与联络资讯 |

## 目录结构

```
esumoon/
├── *.html                 # 7 个页面
├── css/style.css          # 设计系统（配色、字型、元件、RWD）
├── js/main.js             # 行动选单、FAQ 手风琴、卷动进场、表单提示
├── assets/images/
│   ├── site/              # hero、品牌 logo、奖项标志
│   └── products/          # 产品实拍（取自原站）
└── README.md
```

## 本地预览

直接以浏览器开启 `index.html` 即可；或启动简易伺服器：

```bash
# Python
python -m http.server 8000
# 然后开启 http://localhost:8000
```

## 设计

- 字型：Noto Serif SC（标题）+ Noto Sans SC（内文），透过 Google Fonts 载入
- 配色：米白 `#fbf8f2`、炭黑 `#23201b`、金 `#b08d4f`
- 响应式：桌机 / 平板 / 手机三段式断点

## 待办 / 可延伸

- 联络表单目前仅前端提示，未串接寄送服务（可接 Formspree、EmailJS 或自建后端）
- 产品照片为系列代表图，非逐一对应每个 SKU；如需完整商品可再逐项补齐
- 社群连结（Facebook / Instagram）目前为 `#`，待填入实际网址
- 可视需求补上英文 / 简体版本（原站有 en / zh-cn）

## 资料来源说明

文字内容、产品名称与图片素材均取自原 Wix 网站，供品牌自有网站重建之用。
联络资讯已更新为实际资料（Email：Hannah@esumoon.net｜高雄市），
原站页尾的 Wix 范本预设值（info@mysite.com、123-456-7890）已移除。
