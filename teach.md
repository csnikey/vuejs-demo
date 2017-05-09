目前再用vuejs+webpack的团队：
饿了么
苏宁易购触屏版的购物车结算页面已经用 Vue 重构了
https://www.zhihu.com/question/38213423 参考知乎帖子
## nodejs应该学习：
web服务: express, koa, hapi
模板引擎: handlebars, ejs, jade
前端打包: webpack, fis,
任务管理: gulp
单元测试: karma, mocha, jasmine
包管理器: npm, cnpm, yarn
守护进程: pm2
## 计划中的内容
1. 推动运维完成cdn建设，实现前端自动化部署。
2. nodejs项目docker化。
3. 搭建具备mock功能的前端文档平台。
4. 前端项目接入CI系统。
5. 收集线上监控点，搭建基础的前端监控系统。
##vuejs 和后台交互的接口
泻药，用axios，官方推荐的ajax库
## vuejs全部的配置项
https://cn.vuejs.org/v2/api/
## vuejs 实例 都成为vm
构造器写法：
var vm = new Vue({
  // 选项
})
在实例化 Vue 时，需要传入一个选项对象，它可以包含数据、模板、挂载元素、方法、生命周期钩子等选项。全部的选项可以在 API 文档中查看。
## 属性与方法
每个 Vue 实例都会代理其 data 对象里所有的属性：
也就是说vue对象的属性值直接就是对应data里的数值。而且是被响应的

## vuejs的生命周期
如图所示
## 页面中的语法允许变量运算
<a v-bind:href="url"></a>
##修饰符
## 过滤器


