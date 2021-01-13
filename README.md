> 一直对vue很感兴趣，最近使用vue2.0开发了高仿饿了么点餐系统来练练手，不得不说vue真是一个很不错的框架，但是也遇到过一些坑，在这里和大家分享一下

# 点餐系统

> vue2.0、vuex、vue-router、axios、webpack、eslint、better-scroll


## 构建

vue有自己的脚手架构建工具vue-cli,使用起来非常方便，使用webpack来集成各种开发便捷工具，比如：

- 代码热更新，修改代码之后网页无刷新改变，对前端开发来说非常的方便
- PostCss，再也不用去管兼容性的问题了，只针对chrome写css代码，会自动编译生成支持多款浏览器的css代码
- Eslint，统一代码风格，规避低级错误，对于有代码洁癖的人来说是绝对的好东西，不过有些地方的代码校验有时候也挺麻烦的-.-
- bable，ES2015出来已经有一段时间了，但是不少浏览器还没有兼容ES6.有了bable，放心使用ES6语法，它会自动转义成ES5语法。
- Stylus，类似于SASS/SCSS，但是可以不写{}和“：”，使用起来还是很方便的
- ...

除此之外，vue-cli已经使用node配置了一套本地服务器和安装命令等，本地运行和打包只需要一个命令就可以搞定，非常的方便


## 安装步骤

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build
```

## 交流

欢迎热爱学习、忠于分享的盆友一起来交流

- QQ群：930982168

- WeChat: (svip_abin)


