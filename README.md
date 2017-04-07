# 注意：Vue.js 不支持 IE8 及其以下 IE 版本。
# my-project

> A Vue.js project


# 一、创建项目

1、全局安装 vue-cli

$ cnpm install --global vue-cli

2、 创建一个基于 webpack 模板的新项目

$ vue init webpack my-project

3、 这里需要进行一些配置，默认回车即可

This will install Vue 2.x version of the template.

For Vue 1.x use: vue init webpack#1.0 my-project

? Project name my-project

? Project description A Vue.js project

? Author runoob <test@runoob.com>

? Vue build standalone

? Use ESLint to lint your code? Yes

? Pick an ESLint preset Standard

? Setup unit tests with Karma + Mocha? Yes

? Setup e2e tests with Nightwatch? Yes
# 二、进入项目，安装并运行：

$ cd my-project

$ cnpm install

$ cnpm run dev
# 三、开始 Vue 之旅

打开 工程目录下的 App.vue，template 写 html，script写 js，style写样式；

 # 这里有两个坑:
 
  第一。一个组件下只能有一个并列的 div，可以这么写，所以复制官网示例的时候只要复制 div 里面的内容就好。
  
  第二。数据要写在 return 里面而不是像文档那样子写。
## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
