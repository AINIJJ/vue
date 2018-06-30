vue搭建的门户网站
vue第一次实战
ui:elementui
ajax:axios
动态效果：swiper
大部分功能为图文展示
全站单页面开发形式

功能主要是搜索、分页、显示
数据全部为ajax动态获取


vue使用中要注意的点

   ui插件的使用
   vue项目中引用elementui后在页面刚打开没有热更新的情况下组件无法正常显示所以要在组件渲染前进行一次热更新操作。可使用vue生命周期中的钩子函数
   .vue组件中 style使用是全局作用也就是说组件的style里的样式可以作用其他组件里有 相同的class元素
        如果不想全局作用style加属性scoped;但是若想覆盖第三方插件的样式则不能在有scoped的style标签里写。不起作用

