# building
本地构建


#### gulp + babel

```
npm run gulp

npm run babel
```

```
open test/index.html

```

浏览器报错，原因如下：


Babel的作用是帮助转换 ES6 代码为 ES5.
使用 Babel 的 preset-env 转换出来是 CommonJS 标准,浏览器端默认也无法识别CommonJs 规范.需要使用模块打包工具，如 Browserify, Webpack.为代码做一些包裹，就可以在浏览器端使用。
