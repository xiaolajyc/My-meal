我的食谱 PWA（Flat）

文件全部位于根目录，可直接部署到 GitHub Pages 或其他 HTTPS 静态托管。

主要文件：
- index.html：应用主体
- manifest.webmanifest：PWA 配置
- sw.js：离线缓存
- icon-192.png / icon-512.png：PWA 图标
- apple-touch-icon.png：iOS 主屏幕图标

注意：Service Worker 需要 HTTPS（localhost 除外）。
数据主要保存在设备本地，使用应用内“数据备份”进行 JSON 导入/导出。


Google Drive 同步：进入“设置”→“连接 Google Drive”，首次授权后可手动上传到云端或从云端恢复。
