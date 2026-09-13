我的食谱 PWA

文件均在根目录：
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- apple-touch-icon.png

部署：建议上传到 GitHub Pages、Netlify 等 HTTPS 静态网站。
然后用 Android Chrome / iOS Safari 打开网页并添加到主屏幕。

注意：Service Worker 在 file:// 本地双击 HTML 时不会正常工作；本地可以直接打开 index.html 使用网页功能。
