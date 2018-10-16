### 在线体验

通过下面的二维码，可以在手机中体验 Quist-UI (请使用快应用调试器扫码)：

![](http://pfrg4qq0y.bkt.clouddn.com/5baf2aa4N0ccc8797.png)

### 本地体验

1. Clone Quist-UI 仓库到本地
2. 安装依赖 `$ npm install`
3. 在 quist-ui 根目录下执行 `$ npm run watch`
4. 在 quist-ui 根目录下执行 `$ npm run server`
5. Done~

> 如果是在已有项目安装，请按如下代码配置webpack
```js{4}
var path = require('path')
module.exports = {
  postHook: function(webpackConf, options){
    webpackConf.resolve.alias = Object.assign(webpackConf.resolve.alias || {}, {
      '@quist-ui': path.join(process.cwd(), 'components')
    })
  }
}
```

### 反馈沟通

请扫码进入微信群，此群可快速及时地解答问题。

![群二维码](http://pfrg4qq0y.bkt.clouddn.com/image-1539569420758-V2VjaGF0SU1HMS5qcGVn.jpeg)


