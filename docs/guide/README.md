# 介绍
`vue-mooc`是一个使用`Vue`相关技术栈，高仿[慕课网](https://www.imooc.com/)PC端的一个项目，项目中涉及到的技术栈如下：

**Vue生态**:
* `Vue.js`：基础框架，[Vue.js官网](https://cn.vuejs.org/)。
* `Vue-cli3.0`：一个`Vue`官方提供的一个脚手架工具，它提供了标准的目录结构和一些必要的配置，[Vue-cli3.0官网](https://cli.vuejs.org/zh/)
* `Vuex`：数据状态管理工具，[Vuex官网](https://vuex.vuejs.org/)。
* `Vue-router`：路由管理工具，[Vue-router官网](https://router.vuejs.org/)。
* `VuePress`：撰写静态站点的工具(你所看到的本站点是采用`VuePress1.x`)，[VuePress官网](https://v1.vuepress.vuejs.org/)。

**CSS预编译器**：
* `Stylus`：一种`CSS`预编译工具，类似的还有`Sass/Less`，[Stylus官网](https://www.zhangxinxu.com/jq/stylus/)

**数据请求**：
* `axios`：一个非常出名的`HTTP`请求工具，[axios官网](http://www.axios-js.com/)

**Mock数据**：
* `json`数据：本项目接口全部采用手写`json`数据的形式来模拟请求。
* `easy-mock`：使用`easy-mock`接口服务+ `json`数据的形式来`Mock`数据。

## 背景
在目前的业务搬砖中，接触到的项目大多是中后台项目，每日搬砖无非就是拿`element-ui`轮子一把嗦，轮子仔当久了自己也安逸了，痛定思痛后决定当一会轮子的制造者。<br/>
本项目中关于基础组件的封装，全部抛弃使用`element-ui`，而采用自己封装，已达到提高自己的目的，如果你对本项目中封装的公共组件感兴趣的话，请移步这里:point_right: [基础组件](/base/)

**基础公共组件完成情况**：<br/>
<input type="checkbox" checked/> Star(星级评分) <br/>
<input type="checkbox" checked/> Badge(标记)<br/>
<input type="checkbox"/> Empty(空内容)<br/>
<input type="checkbox" checked/> Switch(开关)<br/>
<input type="checkbox"/> Message(消息提示)<br/>
<input type="checkbox"/> MessageBox(消息确认)<br/>
<input type="checkbox"/> Progress(进度条)<br/>
<input type="checkbox"/> Breadcrumb(面包屑导航)<br/>
<input type="checkbox" checked/> Timeline(时间线)<br/>
<input type="checkbox"/> Step(步骤条)<br/>
<input type="checkbox"/> Scroll(滚动组件)<br/>
<input type="checkbox"/> Pagination(分页)<br/>
<input type="checkbox"/> dialog(弹出)<br/>
<input type="checkbox"/> BackTop(返回顶部)<br/>

## 预览&源码地址

如果你想观看此项目的演示效果，请移步:point_right: [预览地址](https://wangtunan.github.io/vue-mooc/#/home) <br/>
如果你需要看一看此项目的源码，请移步:point_right: [源码仓库](https://github.com/wangtunan/vue-mooc)

## 静态站点介绍
本静态站点采用[VuePress1.x](https://v1.vuepress.vuejs.org/)撰写而来，你可以在其官网很方便的找到该如何配置以及搭建属于自己的静态站点，如果你对于官网中的文档不太那么理解，那么请移步:point_right: [从今天开始拿起VuePress打造属于自己的专属博客](https://wangtunan.github.io/blog/vuepress/)，这篇博客也同时提供了一个简单的[VuePress配置Demo](https://github.com/wangtunan/vuepress-blog-demo)，如果你想要一个更贴近于实际的配置，那么请移步:point_right:[本站点的VuePress站点]()

## 部分页面功能演示

### 首页

### 课程页面

### 课程详情页

### 消息中心

### 登陆&注册

### 手记

### 视频播放器