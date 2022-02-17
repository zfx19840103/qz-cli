# qz-cli

项目脚手架，整合各个模板，一键生成模板。提高生产力

[更详细的文档请戳这](https://juejin.im/post/6874815221174075405)

## 效果

![image](./doc/demo.gif)

## 安装

```
npm i qz-cli -g
cnpm i qz-cli -g
yarn add qz-cli -g
```

## 功能

### 项目初始化

```
qz init <you project name>
```

### 帮助

```
qz help
```

### 查看版本

```
qz -V
```

## 提供模板

### 1. vue 2.0

#### 自定义配置

1. 是否使用移动端适配
2. 是否兼容安卓 4.4.0 版本
3. 是否配置微信 sdk
4. 环境选择： 本地、开发、测试、生产、灰度、预发布

### 2. 基于 vue 的活动页 h5 多页面

活动页 h5 多页面配置，并结合 jenkins 和 nginx 实现，每次增加一个页面，只需要在 jenkins 的动态参数中增加一个参数

### 3. 使用 rollup 做构建工具，适用于编写组件或库

rollup 是一款专业打包 js 的打包工具，比起 webpack 打包速度更快，体积更小。适用于组件和库的开发打包。

**自定义配置**

- es – 将软件包保存为 ES 模块文件
- cjs – CommonJS，适用于 Node 和 Browserify/Webpack
- amd 异步模块定义，用于像 RequireJS 这样的模块加载器
- umd – 通用模块定义，以 amd，cjs 和 iife 为一体

## 更多模板还在路上...
