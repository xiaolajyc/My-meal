我的食谱 PWA（Flat）

所有文件均放在同一目录：
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png

部署到 GitHub Pages 等 HTTPS 静态网站后即可安装为 PWA。
不要直接用 file:// 双击测试 PWA；Service Worker 需要 HTTPS 或 localhost。
