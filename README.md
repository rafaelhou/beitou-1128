# 台北慶生行 — 11/28

2026 年 11 月 28–29 日一家四口從台中開車上台北：住台北萬怡（已訂），走路約 11 分到禾禾聽講座、晚上在房內幫大兒子慶生，週日再回台中。
含逐段時間軸、講座三小時的分段對策、萬怡的資料（大多沒讀到官網原文）與步行路線；之前比較過的喜來登、萬豪、晶華等收進折疊區、
以及打電話問飯店的勾選清單（勾選與答案只存在使用者瀏覽器的 localStorage）。

純靜態 HTML + CSS，一小段內嵌 JS，無建置步驟。本機預覽用 root 的 `.claude/launch.json` 裡的 `beitou-1128`（port 4343）。

> repo 與網址仍叫 `beitou-1128`：原本是北投溫泉行，後來改成住晶華，網址沒改。

## 內容的查證標籤

每個事實標「官網查到」、「我估的」或「待確認」。房價、空房、停車費、蛋糕外帶規定官網都沒寫，要打電話。

## 收錄設定

跟其他家庭站一致：`robots.txt` 擋 AI 爬蟲，每頁 `noindex`，`_headers` 加 `X-Robots-Tag`。

## 部署

- GitHub Pages：<https://rafaelhou.github.io/beitou-1128/>（main 分支根目錄）
- Cloudflare Pages：<https://beitou-1128.pages.dev>（Git 連結，push 到 main 自動部署）
