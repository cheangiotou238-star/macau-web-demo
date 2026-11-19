# 目前脈絡（Active Context）

- Git main 綁定遠端 origin（github.com/cheangiotou238-star/macau-web-demo），最新 commit 5f8f09d 已 push。
- 根目錄 `index.html`：國際化工作室封面「Stride Web Co」（預設英文、英/繁中/葡三語）。
- `shops/ingenuity-dental/index.html`：匠心牙科中心 Artisan Dental（三語）商業版。
  - 本機素材 `assets/`（brand-logo + clinic-environment + clinic-photo-1~6），全部 `<img>` 加 onerror 防破圖；品牌標誌置於關於我們，新增「診所分享與環境」圖庫並標註引用自 FB。
  - 地址：澳門皇朝建興龍廣場9樓B座（地圖仍用宋玉生廣場258號精確定位）；電話 +853 6825 4553（tel + 複製）、Email、WeChat ArtisanDental（複製微訊號/預約內容）、FB/Messenger 匠心牙科中心、IG ArtisanDental.mo。
  - 移除價目表格 →「預約與諮詢」區塊（WhatsApp/WeChat/Email 通道 + 表單）；評論改真實亮點（溫馨環境、前台親切、迎賓飲品、不硬銷、洗牙溫和、兒童扭蛋、無障礙）。
  - 三語 key 133 組完全同步；JS 通過 node --check；JSON-LD 補 description 與 m.me sameAs。
- MCP `fetch` 用 `npx mcp-server-fetch`。
- 下一步：啟用 GitHub Pages。
