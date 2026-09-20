我的食谱 PWA Flat
版本：v1.1.2

Google Drive 多设备同步：
- 使用 Google Identity Services + Drive API drive.file
- 已授权设备优先静默续期 access token，避免频繁重新登录
- 自动同步在 token 过期后尝试静默续期，不主动弹出登录窗口
- 若 Google 登录会话本身已失效，只在设置中手动连接时重新授权

部署：将全部 7 个文件放在同一目录，通过 HTTPS/localhost 访问。
