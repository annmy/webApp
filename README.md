# webApp
a simple webApp
------------
由Koa、Vue、Zepto等框架结合HTML5开发的一个包含阅读器功能的书城App。
整个过程分为几个比较复杂的模块进行开发、如阅读器、书城首页、搜索模块。

------------
在线演示地址 http://annmytest.duapp.com/
手机端效果要好
------------

常用知识点
------------

* ES6的Promise对象：用来传递异步操作的消息，充当异步和回调的中介，免除重复繁琐的回调函数嵌套
* HTML5的localStorage：用来做客户端存储，如存储用户所看的文章的ID或者阅读习惯
* ajax：发送请求获得数据后结合Vue对数据做渲染
* transform属性: 页面滑动
* 触屏事件: touchstart、touchmove、touchend


完成功能
-------
  - [x] 书城首页
  - [x] 书籍详情页
  - [x] 各类频道页
  - [x] 阅读器
  - [x] 搜索功能
  - [ ] 个人中心
  - [ ] 频道切换
  - [ ] 性能优化
目录
-------
  * mock: 模拟数据,充当数据库的作用
  * service: 读取数据,充当前后端的纽带。大部分数据是通过mock读取，少部分真实数据是直接发起http请求去获取。
  * static: 静态资源
  * view: ejs模板
  * app.js: 项目入口
  * package.json: 项目所需依赖

项目依赖
-------
  * koa: 基于Node.js平台的web开发框架
  * koa-route: 用来设置路由
  * koa-static-server: 提供静态资源服务
  * co-views: 用来设置模板引擎
  * ejs: ejs模板引擎
  

运行项目
-------
```
  $ npm install
  $ node app.js
```
