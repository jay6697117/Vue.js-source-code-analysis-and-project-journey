作者简介

Jeskson，前端开发负责人，活跃于CSDN（博客专家），掘金，Github，知乎，简书（5万粉），腾讯云社区专栏作者等开源社区，接触过许多优秀项目的代码，丰富的专业知识和开发经验，网上发表博客，所有综合平台累计访问量近百万人次，深受读者好评。
本书从Vue框架的基础结构讲起，逐步深入Vue进阶实战，并再最后配合项目实战案例，重点演示了Vue项目开发中的一些应用。再系统地讲解VUE的相关知识之余，本书力图使读者对Vue项目开发产生更深入的理解。
本书涵盖的主要内容为VUE的基本简介，语法，选项，内置组件，项目化，使用Vue开发电商类网站，使用Vue开发企业官网，使用VEU开发移动端等。
本书内容通俗易懂，案例丰富，实用性强，特别适合VUE的初学者和从业人员阅读，同时也适合职业生涯遇到“瓶颈”的前端从业人员和编程爱好者，也适合作为相关培训机构的教材。

《Vue.js项目之旅》书籍源码

```
目录
目录	1
第一章 初识Vuejs3.0	1
第二章 入门基础	1
第三章 Vue.js的组件	3
第四章 细说API的使用	3
第五章 关于实例	6
第六章Vue-router的使用	8
第七章Vuex的使用	8
第八章 Vue的项目	9
前言

目录
第一章 初识Vuejs3.0
1.1 Vue.js是什么
1.2 Vue.js 3.0的新特性
1.3 为什么要使用Vue
1.4 了解MVVM模式
1.4 第一个Vuejs项目
第二章 入门基础
2.1 模板语法
2.1.1 模板语法
2.1.2 指令的使用
2.1.3 缩写形式
2.2 计算属性与侦听器
2.2.1 计算属性
2.2.2 侦听器的使用
2.3 class与style的使用
2.3.1 绑定class
2.3.2 绑定内联样式
2.4 条件渲染
2.4.1 v-if的使用
2.4.2 v-show的使用
2.4.3 v-if与v-show
2.5 列表渲染
2.5.1 列表中的v-if
2.5.2 维护状态
2.5.3 数组更新检测
2.5.4 显示过滤、排序后的结果
2.5.5 列表的使用
2.6 事件说明
2.6.1 监听事件
2.6.2 事件处理方法
2.6.3 内联处理器中的方法
2.6.4 事件修饰符的使用
2.6.5 按键修饰符的使用
2.6.6 系统修饰符的使用
2.7 表单的使用
2.7.1 基本用法
2.7.2 值的绑定
2.7.3 修饰符
第三章 Vue.js的组件
3.1 组件的使用
3.1.1 组件的基本使用
3.1.2 组件的复用
3.1.3 组件的传递
3.1.4 单个根元素
3.1.5 监听子组件事件
3.1.6 使用插槽
3.1.7 动态组件的使用
3.2 实践组件
3.2.1 组件注册
3.2.2 了解prop
3.2.3 自定义事件
3.2.4 了解插槽
3.2.5 动态组件与异步组件
第四章 细说API的使用
4.1 全局配置
4.1.1 silent说明
4.1.2 了解optionMergeStrategies
4.1.3 了解devtools
4.1.4 了解errorHandler
4.1.5 了解warnHandler
4.1.6 了解ignoredElements
4.1.7 了解keyCodes
4.1.8 了解performance
4.1.9 了解productionTip
4.2 全局API
4.2.1 Vue.extend说明
4.2.2 Vue.nextTick说明
4.2.3 Vue.set说明
4.2.4 Vue.delete使用
4.2.5 Vue.directive使用
4.2.6 Vue.filter使用
4.2.7 了解Vue.component
4.2.8 Vue.use使用
4.2.9 Vue.mixin使用
4.2.10 Vue.compile使用
4.2.11 Vue.observable使用
4.2.12 Vue.version说明
4.3 数据
4.3.1 data说明
4.3.2 props使用
4.3.3 propsData使用
4.3.4 computed使用
4.3.5 methods使用
4.3.6 watch使用
4.4 了解DOM
4.4.1 了解el
4.4.2 template使用
4.4.3 了解render
4.4.4 了解renderError
4.5 生命周期钩子
4.5.1 beforeCreate的使用
4.5.2 created的使用
4.5.3 beforeMount的使用
4.5.4 mounted的使用
4.5.5 beforeUpdate的使用
4.5.6 updated的使用
4.5.7 activated的使用
4.5.8 deactivated的使用
4.5.9 beforeDestroy的使用
4.5.10 destroyed的使用
4.5.11 errorCaptured的使用
4.6 资源
4.6.1 directives的使用
4.6.2 filters的使用
4.6.3 components的使用
4.7 组合
4.7.1 parent的使用
4.7.2 mixins的使用
4.7.4 extends的使用
4.7.5 provide与inject使用
4.8 其余API
4.8.1 了解name
4.8.2 了解delimiters
4.8.3 了解functional
4.8.4 了解model
4.8.5 了解inheritAttrs
4.8.6 了解comments
第五章 关于实例
5.1 属性
5.1.1 vm.$data的使用
5.1.2 vm.$props的使用
5.1.3 vm.$el的使用
5.1.4 vm.$options的使用
5.1.5 vm.$parent的使用
5.1.6 vm.$root的使用
5.1.7 vm.$children的使用
5.1.8 vm.$slots的使用
5.1.9 vm.$scopedSlots的使用
5.1.10 vm.$refs的使用
5.1.11 vm.$isServer的使用
5.1.12 vm.$attrs的使用
5.1.13 vm.$listeners的使用
5.2 数据
5.2.1 vm.$watch的使用
5.2.2 vm.$set的使用
5.2.3 vm.$delete的使用
5.3 事件
5.3.1 vm.$on的使用
5.3.2 vm.$once的使用
5.3.3 vm.$off的使用
5.3.4 vm.$emit的使用
5.4 生命周期
5.4.1 vm.$mount的使用
5.4.2 vm.$forceUpdate的使用
5.4.3 vm.$nextTick的使用
5.4.4 vm.$destroy的使用
5.5 其他
5.5.1 key的说明
5.5.2 ref的说明
5.5.3 is的说明
5.5.4 slot的说明
5.5.5 slot-scope的说明
5.5.6 scope的说明
5.5.7 component的说明
5.5.8 transition的说明
5.5.9 transition-group的说明
5.5.10 keep-alive的说明
5.5.11 slot的说明
第六章Vue-router的使用
6.1  Vue-router起步
6.1.1  vue-router的使用
6.1.2 动态路由匹配
6.1.3 嵌套路由
6.1.4 编程式的导航
6.1.5 命名路由
6.1.6 重定向与别名
6.1.7 路由组件传参
6.2  vue-router实践
6.2.1 导航守卫
6.2.2 过渡效果
6.2.3 滚动行为
第七章Vuex的使用
7.1  vuex的简介
7.1.1  state
7.1.2  getter
7.1.3  mutation
7.1.4  action
7.1.5  module
7.1.6  Vuex的实践
第八章 Vue的项目
8.1 Todolist的项目
8.1.1 项目说明
8.1.2 项目源码
8.1.3 项目效果
8.2 vue登录项目
8.2.1 项目说明
8.2.2 项目源码
8.2.3 项目效果
8.3  vue商城项目
8.3.1 项目说明
8.3.2 项目源码
8.3.3 项目效果
8.4  vue博客项目
8.4.1 项目说明
8.4.2 项目源码
8.4.3 项目效果
8.5  vue小店项目
8.5.1 项目说明
8.5.2 项目源码
8.5.3 项目效果
```