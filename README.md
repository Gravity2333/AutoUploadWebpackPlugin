使用方法
```js
    // 在你生产模式的plugin中配置: 
    plugins: [
        new AutoUploadWebpackPlugin({
            host: '你的服务器地址',
            username: '用户名称',
            password: '密码',
            serverDir: '静态资源服务器地址'
        })
    ]
```