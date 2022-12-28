# webrtc-demo

## 安装依赖

```
npm install
npm run serve
npm run node-local
```
## 服务器上用 pm2 启动：

```
pm2 start server.js
```

## web资源部署后 navigator 获取不到 mediaDevices 实例的解决方案（navigator.mediaDevices为undefined）
```
由于浏览器的安全策略导致了这个问题，目前经尝试，在以下几种情况中 navigator.mediaDevices 可以正常使用：

1、访问地址为 localhost
2、访问地址为 https
3、文件访问：file:///
```
