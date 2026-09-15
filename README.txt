我的食谱 PWA（Flat）

文件全部位于根目录，可直接部署到 GitHub Pages 等 HTTPS 静态网站。
首次访问后可通过浏览器“添加到主屏幕/安装应用”安装为 PWA。

包含：
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png
- 本地 localStorage 数据保存
- IndexedDB 跟做照片保存
- JSON 完整备份/恢复

注意：Service Worker 需要 HTTPS（localhost 开发环境除外）。
