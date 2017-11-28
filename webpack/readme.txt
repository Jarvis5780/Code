参考：https://segmentfault.com/a/1190000006178770

//全局安装webpack、webpack-dev-server
npm install webpack -g  //webpack
npm install webpack-dev-server -g  //全局安装直接使用webpack-dev-server --inline --hot


//指定打包方式文件等
webpack ./entry.js bundle.js  


//直接使用 webpack会按照配置文件方式生成打包文件
新建 webpack.config.js  


//初始化package.json
npm init


//npm安装jquery
npm install jquery  --save-dev


//安装bootstrap
npm install bootstrap  --save-dev


//安装css 、js相关loader
npm install css-loader style-loader babel-core babel-loader babel-plugin-transform-runtime babel-preset-es2015 babel-preset-stage-0 babel-runtime --save-dev


//常用命令
webpack  --display-modules
webpack  --display-reasons
webpack -p  //压缩
webpack -w  //修改刷新就行


//局部安装
//主要项目中name不能有webpack名称
npm install webpack-dev-server --save-dev
node_modules/.bin/webpack-dev-server --inline --hot  //局部安装请使用相对路径命令启动  npm run hot（配置package.json）


//插件
npm install --save-dev html-webpack-plugin

