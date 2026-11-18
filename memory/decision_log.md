# 決策記錄（Decision Log）

- 2026/11/17：建立專案 `.clinerules`（RWD 手機優先、繁中為主預留英/葡、WhatsApp 浮動預約按鈕）。
- 2026/11/17：本機未安裝 `uv`，將 `fetch` MCP 由 `uvx mcp-server-fetch` 改為 `npx mcp-server-fetch`。
- 2026/11/17：初始化 Git（預設分支 `main`）、綁定遠端 `origin`，以 `gh` CLI 建立公開倉庫並完成首次 Commit 與 Push。
- 2026/11/17：建立首個子商戶頁 `shops/ingenuity-dental/index.html`（牙科診所），新增「顧客好評」區塊、`aggregateRating` 結構化資料與 Google Maps 定位。
- 2026/11/18：移除根目錄假茶餐廳測試頁，改為中性工作室簡介頁；匠心牙科升級為完整商業版（真實圖片、線上預約表單、社交按鈕、WeChat QR modal），並 Commit + Push。
- 2026/11/18：根目錄 `index.html` 改版為國際化工作室封面「Stride Web Co」——預設英文、英/繁中/葡三語、移除澳門地址與區號電話、Email 聯絡（hello@stridewebco.com）、JSON-LD 改為 Organization（stridewebco.com）；`shops/ingenuity-dental/` 保持不變。
- 2026/11/18：匠心牙科英文品牌更名為「Artisan Dental」並完成上線前資料校準（真實地址「澳門宋玉生廣場258號建興龍廣場9樓B座」、Email artisandental.macau@gmail.com、電話 +853 6825 4553、FB+IG 官方連結並移除 RED 與 WeChat 示範 QR、預約表單改為 WhatsApp/Email 直送、桌面 Header 單行 Flexbox、JSON-LD 補 email 與 sameAs），Commit + Push。
