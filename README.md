# MapTilesViewer 🌍🗺️

瓦片网格查看器 🧩

本项目用于可视化在线或本地地图瓦片的分布和索引。通过 [map-grid.html](map-grid.html) 页面，用户可以：

- 加载在线或本地瓦片地图（支持自定义 URL 模板）🌐📁
  - a. 加载在线瓦片地图：输入瓦片 URL 模板，如 `https://server.com/tiles/{z}/{x}/{y}.png` 🌏
  - b. 加载本地瓦片地图：输入本地瓦片文件夹路径，如 `file:///F:/Desktop/MapTiles/GMRT/{z}/{x}/{y}.png` 💾
- 显示瓦片网格及其索引编号 🔢
- 切换网格显示，辅助定位瓦片索引 🔲
- 支持自定义瓦片层级和格式（XYZ/TMS）⚙️

## 使用方法 🚀

1. 打开 [map-grid.html](map-grid.html) 文件即可在浏览器中使用。🖥️
   - 如果是 http 请求 ， 请拉取到本地使用，浏览器安全策略要求，HTTPS 页面中的资源请求也必须为 HTTPS，否则会被拦截或自动升级。
2. 可在页面右上角输入自定义瓦片 URL 模板，支持本地文件和在线服务。✏️
3. 点击“切换网格”按钮显示/隐藏瓦片索引网格。🔀

## 依赖 📦

- [Leaflet.js](https://leafletjs.com/) 地图可视化库（通过 CDN 引入）🧭

## 示例 🖼️

默认加载 Windy 在线底图 叠加自定义地图
