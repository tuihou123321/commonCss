##  通用commonCss样式库


### 引入
> npm i xzcommoncss

npm 仓库地址：https://www.npmjs.com/package/xzcommoncss

### 使用方式
-[x] 默认px,rem两种写法
-[x] 支持引入全部/单个样式

> rem 默认基准值是基于375px下的100px

### 设计思想
- 样式与业务逻辑分离，所以样式不应该有业务属性名
- 布局模块化，常用的布局方式，封装好，可快速使用，稍加修改
- 样式最小颗粒度，组合性强
- 支持各浏览器兼容写法


### 编译打包
- koala编译index.scss,源码sass打包成css的方式


### 参考资料：
- [我是如何对网站CSS进行架构的](http://www.zhangxinxu.com/wordpress/2010/07/%e6%88%91%e6%98%af%e5%a6%82%e4%bd%95%e5%af%b9%e7%bd%91%e7%ab%99css%e8%bf%9b%e8%a1%8c%e6%9e%b6%e6%9e%84%e7%9a%84/)
