TSMC Vocabulary PWA v2

本版本更新：
1. 手機版版面重新調整：縮短頂端導覽、四個功能按鈕更適合小螢幕、選項與按鈕更容易觸控。
2. 新增「完整題庫 288 題」模式：會把 288 個單字全部出完，並在每題顯示進度。
3. 保留隨機 10 題、單字表、錯題本、錯題再測、分數與瀏覽器 localStorage。
4. 加入 PWA manifest、Service Worker、PNG App Icon。
5. GitHub Pages 部署後可用手機加入主畫面。

GitHub Pages：
- Repository 根目錄放 index.html、manifest.webmanifest、sw.js、icons。
- Pages Source：Deploy from a branch
- Branch：main
- Folder：/(root)
- 必須使用 HTTPS。

iPhone：
Safari 開啟網站 → 分享 → 加入主畫面。

Android：
Chrome 開啟網站 → 安裝應用程式／加入主畫面。


v4：強化「清除全部紀錄」，會清除錯題本與所有測驗統計，並立即將作答題數、累積答對、最佳正確率歸零；同時更新 Service Worker 快取版本。
