# 技术栈和开发工具的建议

## 1 技术栈

  建议使用 react（es6 + jsx） + redux + sass + node 。 原本更倾向于使用Vue + flux + sass + node,由于要兼容IE 8 所以推荐react。
  
### 1.1 react 
  [文档](https://facebook.github.io/react/)。使用组装的设计可以很好的完成页面组件化,基本上可以不借助继承等实现页面中各种粒度的组件模型化
  
### 1.2 redux
  [文档](http://redux.js.org/)易用的状态管理方式,在前端实现路由的SPA中能带来很大的利,如果实现跟现有政采云平台中后台管理功能则不需要。
 
### 1.3 sass
  [文档](http://www.sass-lang.com/)建议使用sass组织样式,将与主题相关的样式值参数化,提取成theme变量,以方便的切换主题和风格。还可以将一些常用的内容如圆角样式、动画、transition等使用mixin函数化模块化组织。
  增加css灵活性可重用性。使用gulp,工具上可以使用gulp-sass、gulp-sass-lint。使用Webpack工具上可以使用sass-loader.
  
### 1.4 node
  [下载]()可以基于node来编写一些辅助的脚本工具来减少重复的劳动,或使优化调试的方法,如自动化生成mock 数据 ,自动化生成表单、列表页面的html,来提高开发的效率。  
  
##  2 工具链

   建议使用 webstorm 或 atom,+ VirtualBox. 两者都有丰富的插件可以使用。建议按需求安装,可以给开发带来很大的便利,也可以做一些代码检测如安全、性能、查错等。
   * [webstorm](http://www.jetbrains.com/webstorm/?fromMenu)
   * [atom](https://atom.io/)
   * [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
   * [node](https://nodejs.org/en/)
   * [gulp](http://gulpjs.com/)
   * [webpack](https://webpack.github.io/)
   * [JsDoc](https://github.com/jsdoc3/jsdoc)[官网](http://usejsdoc.org)
   * [gulp-jsdoc3](https://github.com/mlucool/gulp-jsdoc3)
   * [gitbook](http://www.gitbook.com/)
   
   
   
## 3 JSDOC 或 Gitbook 文档生成
   * [jsdoc](http://usejsdoc.org)
   * [gulp-jsdoc3](https://github.com/mlucool/gulp-jsdoc3)
   * [gitbook](http://www.gitbook.com)
   
   
## 4 前端常用的文档参考网站
   
   * [MDN: https://developer.mozilla.org/zh-CN/](https://developer.mozilla.org/zh-CN/)
   * [Google Developer](https://developers.google.com/)
   * [MSDN API https://msdn.microsoft.com/library](https://msdn.microsoft.com/library)
   * [Nodejs Doc: https://nodejs.org/en/docs/](https://nodejs.org/en/docs/)
   * [Vuejs http://vuejs.org/](http://vuejs.org/)
   * [React https://facebook.github.io/react/](https://facebook.github.io/react/)