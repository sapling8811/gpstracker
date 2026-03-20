# gpstracker

## 🌐 直接開啟網址

本專案已部署至 **GitHub Pages**，合併至 `main` 分支後即可透過以下網址直接使用：

| 頁面 | 網址 |
|------|------|
| 🏠 首頁 | https://sapling8811.github.io/gpstracker/ |
| 🍜 小吃店 POS 系統 | https://sapling8811.github.io/gpstracker/pos.html |
| 📍 GPS 追蹤傳送 | https://sapling8811.github.io/gpstracker/sender.html |

> **注意**：部署由 GitHub Actions 自動完成，每次推送到 `main` 後約 1–2 分鐘生效。  
> 若網址顯示 404，請至 Repository → **Settings → Pages** 確認 Source 已設為 **GitHub Actions**。

---

## 📦 頁面說明

### 小吃店 POS 系統 (`pos.html`)
- 分類菜單點餐（主食、小吃、飲料、甜點）
- 訂單管理、結帳找零
- 歷史訂單記錄（儲存於瀏覽器 localStorage）
- 菜單新增／編輯／刪除
- 離線可用，無需後端

### GPS 追蹤傳送 (`sender.html`)
- 每分鐘自動取得目前 GPS 座標並傳送至 Cloudflare Worker