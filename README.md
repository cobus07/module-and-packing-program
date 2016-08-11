# 模块化和打包方案收集


模块化方案

RequireJS

AMD 方案, 常用的 define 语法, 异步加载模块, 目前很多支持:

官网 http://requirejs.org/

Github https://github.com/jrburke/requirejs

Getting started https://gist.github.com/willurd/6054834

打包工具 http://jamjs.org/

相似方案:

ozjs: http://ozjs.org/cn/

Browserify

CommonJS 方案, 共用 NPM 部分平台无关的模块:

官网 http://browserify.org/

Github https://github.com/substack/node-browserify

教程 http://superbigtree.tumblr.com/post/54873453939/introduction-to-browserify

NPM npmjs.org

Browserify 兼容 Node 模块引用语法和 Node 模块化文件加载方案,

浏览器端运行前需要完成代码的合并, 并配合 SourceMap 进行调试.


相似方案:

commonjs-everywhere https://github.com/michaelficarra/commonjs-everywhere

stitch https://github.com/sstephenson/stitch

onejs https://github.com/azer/onejs

gluejs https://github.com/mixu/gluejs

SeaJS


支付宝的前端加载器, 遵循 CMD 规范, 打包工具是 SPM.

官网 http://seajs.org/docs/

Github https://github.com/seajs/seajs/issues

Why SeaJS http://cyj.me/why-seajs/

官方模块 http://aralejs.org/

打包工具 SPM http://docs.spmjs.org/

第三方源 https://spmjs.org/

相关方案:

BravoJS https://code.google.com/p/bravojs/

Component

Node.js 社区另一个为前端优化的模块方案, 类似 Browserify, 但鼓励将 HTML/CSS 打包到模块.

模块保存在 Github.

模块列表 http://component.io/

作者写的介绍 http://tjholowaychuk.com/post/27984551477/components

Github https://github.com/component

ES6

ES6 Modules https://gist.github.com/wycats/51c96e3adcdb3a68cbc3

jspm.io http://jspm.io/

JS 规范里制定的模块化方案, 浏览器实现还没, 不过有模块可以提供类似功能.

es6-module-transpiler https://github.com/square/es6-module-transpiler

my.js https://github.com/hax/my.js

Modjs

腾讯的.

官网 http://madscript.com/modjs/

Github https://github.com/modulejs/modjs

AngularJS

官网 http://angularjs.org/

Github https://github.com/angular

模块列表 http://ngmodules.org/

Package Manager

Bower

来自 Twitter 的模块管理方案, 或者仅仅是包管理工具.. 模块直接从 Github 下载

官网 http://bower.io/

模块列表 http://sindresorhus.com/bower-components/

相关方案:

Yeoman http://yeoman.io/
Ender

官网 http://ender.jit.su/
Volo

官网 http://volojs.org/
代码打包

Linner

Github https://github.com/SaitoWu/linner
WebPack

Github https://github.com/webpack/webpack

Home Page http://webpack.github.io/#/home

UMD

Github https://github.com/umdjs/umd

uRequire Documents http://urequire.org/quick-introduction
方案的对比

So, you want to use require() in the browser…http://blog.brianbeck.com/post/10667967423/node-js-require-in-the-browser

NPM vs JAM, RequireJS vs Browserify vs

Enderhttp://www.reddit.com/r/javascript/comments/vc9d9/npm_vs_jam_requirejs_vs_browserify_vs_ender/

The State of Javascript Package Managementhttp://wibblycode.wordpress.com/2013/01/01/the-state-of-javascript-package-management/

Front-End Package Manager https://github.com/wilmoore/frontend-packagers

Package Managers: An Introductory Guide For The Uninitiated Front-End

Developerhttp://tech.pro/tutorial/1190/package-managers-an-introductory-guide-for-the-uninitiated-front-end-developer
