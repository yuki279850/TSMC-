# TSMC Vocabulary PWA

這個資料夾是一個可安裝到手機主畫面的 PWA。

## 使用方式
1. 將整個資料夾部署到 HTTPS 網站（例如 GitHub Pages、Netlify、Vercel 或自己的 HTTPS 網站）。
2. 用手機瀏覽器開啟 `index.html`。
3. Android Chrome 通常會顯示「安裝到主畫面」提示；iPhone/iPad 可在 Safari 使用「加入主畫面」。
4. 安裝後可像 App 一樣開啟；Service Worker 會快取網站，之後可離線使用已快取內容。

注意：直接用 `file://` 開啟 HTML 不會完整啟用 PWA 安裝功能；需要 HTTPS（localhost 開發環境除外）。
