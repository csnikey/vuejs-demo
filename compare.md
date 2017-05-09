## 参考链接
https://cn.vuejs.org/v2/guide/comparison.html
## 与react的区别
### 性能
绝大部分的性能都会消耗在虚拟的dom上，这点和react一样都采用的虚拟dom,
组件发生变化，不需要重新渲染，而react需要重新渲染
### 语法
vue还是基本使用html,css的样式，也支持jade的模板引擎
## 组件样式
样式支持组件级别的，而jsx的语法是基于js的，比较晦涩难懂，但这也是react的优点，让你可以用一种语言完成开发
### 开发中
vue最快每秒10帧，而react不超过1，因为存在很多检查
### 规模 向上拓展
Vue 和 React 都提供了强大的路由来应对大型应用
者另一个重要差异是，Vue 的路由库和状态管理库都是由官方维护支持且与核心库同步更新的。React 则是选择把这些问题交给社区维护，因此创建了一个更分散的生态系统。但相对的，React 的生态系统相比 Vue 更加繁荣。
Vue 提供了Vue-cli 脚手架，能让你非常容易地构建项目，包含了 Webpack，Browserify，甚至 no build system。React 在这方面也提供了create-react-app，但是现在还存在一些局限性
### 向下拓展
react学习曲线陡峭，在你开始学 React 前，你需要知道 JSX 和 ES2015，因为许多示例用的是这些语法。你需要学习构建系统，虽然你在技术上可以用 Babel 来实时编译代码，但是这并不推荐用于生产环境。
vuejs向下拓展像jq,向上像react。

### 本地渲染
weex在和vue合作 但是成熟度也不能和 ReactNative 相抗衡

## 与ng2对比
###性能
 Vue 2 相比 Angular2 是更快的
###灵活性
 Vue 相比于 Angular 2 则更加灵活，Vue 官方提供了构建工具来协助你构建项目，但它并不限制你去如何构建。有人可能喜欢用统一的方式来构建，也有很多开发者喜欢这种灵活自由的方式
### 学习曲线
 开始使用 Vue，你使用的是熟悉的 HTML、符合 ES5 规则的 JavaScript（也就是纯 JavaScript）。有了这些基本的技能，你可以快速地掌握它(指南)并投入开发 。
Angular 2 的学习曲线是非常陡峭的。即使不包括 TypeScript，它的开始指南中所用的就有 ES2015 标准的 JavaScript，18个 NPM 依赖包，4 个文件和超过 3 千多字的介绍，这一切都是为了完成个 Hello World。而Vue’s Hello World就非常简单。甚至我们并不用花费一整个页面去介绍它。