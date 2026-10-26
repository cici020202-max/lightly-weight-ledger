# 轻记 · 体重与热量账本

HTML + Tailwind CSS + 原生 JavaScript，本地单用户应用。

- `index.html`：页面结构
- `styles.css`：视觉规范与组件
- `app.js`：记录、换算、趋势、localStorage 持久化
- `vendor/tailwind-browser.js`：本地 Tailwind Browser 4，预览无需访问 CDN
- `server.js`：本地服务器，源文件修改后自动刷新预览

运行：`node server.js`，打开 http://127.0.0.1:4173。

首次为真实空账本，点击“查看有数据的示例”体验完整界面。示例数据只存内存，不覆盖真实数据。关闭示例即可回到真实记录。数据保存在同一浏览器、同一网址的 localStorage，清除网站数据会丢失记录。

Tailwind Browser 适合此本地原型；正式发布时建议使用 Tailwind CLI 编译静态 CSS。
