# 跨域调用 GPS 

## 使用方法
- 使用 iframe 加载 `iframe.html`
- 在本地监听 `message` 事件
- 用 postMessage 向 iframe 调用 `getGps` 方法
- 示例可以参考 `index.html`
> 如果需要在 IOS10 以上设备使用 GPS 需要把 `iframe` 放到 `https` 服务器下。可以参考 [Web 地图 GPS 定位](http://zyou.top/blog/map)

