# travel-website

2026 秋季拜訪企鵝：單一 HTML 旅行手帖。

公開版保留原版設計與行程，已移除私人車票網址、預約編號與乘車 QR 資料。車票請自行保存在手機。

## 啟用 GitHub Pages

1. 開啟專案的 [Settings → Pages](https://github.com/clyin121-rgb/travel-website/settings/pages)。
2. 在 **Build and deployment → Source** 選擇 **Deploy from a branch**。
3. 選擇 **main** 與 **/(root)**，按 **Save**。
4. 等待 GitHub 完成部署，Pages 頁面會顯示實際網站網址。

預設網址為 `https://clyin121-rgb.github.io/travel-website/`，使用 GitHub 提供的網址不必購買網域。

## 搜尋與公開範圍

HTML 已設定 `noindex, nofollow`，要求搜尋引擎不要收錄。這不是密碼保護；知道網址的人仍能開啟網站，公開儲存庫的程式碼也可能被搜尋到。

## 下架

到 **Settings → Pages → Build and deployment**，將 Source 設為 **Deploy from a branch**，Branch 改成 **None**，按 **Save**，即可停止發布，不必刪除原始檔。

下架不能收回他人已下載的 HTML 副本。
