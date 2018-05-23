# 七牛云上传JS SDK文件

by HyperQing 2018-03-15

**自带完整token生成功能，适用于 DCloud、ApiCloud 等 H5 App 应用环境。**

**尽管可运行于桌面和手机的谷歌浏览器及其他现代浏览器，但不推荐使用。因为除了js文件较大1.4MB左右，且 token 生成操作应在后端进行。**

如果需要在浏览器中使用，建议使用以下这个JS文件（无自带token生成功能，需要在后端生成）。
https://www.npmjs.com/package/qiniu-js

## qiniu.js

最终生成文件所在目录：`public/qiniu.js`

使用示例见：`index.html`

## Webpack 打包

全局安装Webpack(已安装可以忽略此步骤)。
```
cnpm install webpack -g
```
安装本项目依赖
```
cnpm install
```
执行打包
```
webpack
```

## 七牛云文档

https://developer.qiniu.com/kodo/sdk/1289/nodejs

该文档虽然是Node.js SDK的，实际上经过打包后的qiniu.js，可以在浏览器中完全按照文档说明来使用。
