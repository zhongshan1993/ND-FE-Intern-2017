# 工程院 2017 Web前端实习资料

## 练习任务

### 初级任务（响应式页面）

页面设计图待定...

要求：

1. 按照正确的语义使用HTML标签
2. CSS基础的布局，定位，排版，盒模型，选择器特殊性等知识
3. 页面效果优先考虑是否能用CSS3实现
4. 简单的交互效果，用原生JS实现，不要使用jQuery等第三方库
5. 页面要兼顾移动端和PC端的排版效果（响应式）

### 进阶任务（单页应用）

用 `http://pm25.in/api_doc` 提供的空气质量数据，做一个简单的单页应用，
可以用任意框架来写，需要使用构建工具对代码进行压缩，预处理，单元测试，Lint
等等

应用原型待定...

要求（暂定）：

1. 查看常驻城市的空气质量
2. 查看全国的空气质量指数排名
3. 添加其他城市，设置常驻城市
4. ......

### 任务提交以及Review方式

用自己的github账号fork本仓库，初级任务在 `basic` 目录下进行开发，进阶任务在 `advanced` 目录下进行开发。
开发完一个任务后，向上游分支（本仓库）Pull Request，对代码的Review会直接在github上进行。Pull Request
之前，请在任务目录下提供一个 `readme.md` 文档说明如何运行这个项目。

## 学习资料

为前端新人收集的一些学习资料，欢迎PR补充，部分资料为英文并且需要科学上网才能访问

### HTML + CSS

在线教程：

[w3school](http://www.w3school.com.cn/)

[MDN：学习Web开发](https://developer.mozilla.org/zh-CN/docs/learn)

推荐书单：

[《响应式Web设计：HTML5和CSS3实战》](http://www.ituring.com.cn/book/1817)

[《CSS权威指南》](https://book.douban.com/subject/2308234/)

[《精通CSS》](https://book.douban.com/subject/4736167/)

[《CSS揭秘》](http://www.ituring.com.cn/book/1695)

### JavaScript

在线教程：

[JavaScript秘密花园](https://bonsaiden.github.io/JavaScript-Garden/zh/)

[JavaScript标准参考教程————阮一峰](http://javascript.ruanyifeng.com/)

[ES6入门](http://es6.ruanyifeng.com/)

推荐书单：

[《JavaScript语言精粹》](https://book.douban.com/subject/3590768/)

[《JavaScript高级程序设计》](http://www.ituring.com.cn/book/946)

[《JavaScript忍者秘籍》](http://www.epubit.com.cn/book/details/4011)

[《你不知道的JavaScript（上）》](http://www.ituring.com.cn/book/1488)

[《你不知道的JavaScript（中）》](http://www.ituring.com.cn/book/1563)

[《你不知道的JavaScript（下）》](http://www.ituring.com.cn/book/1666)

[《深入浅出ES6》](http://www.infoq.com/cn/minibooks/ES6-in-Depth?)

[《Promise迷你书》](http://liubin.org/promises-book/)

### 其他

代码风格：

[airbnb JS编码风格指南](https://github.com/airbnb/javascript)
(PS：链接中有airbnb其他语言的编码风格指南)

HTTP：

[《图解HTTP》](https://book.douban.com/subject/25863515/)

Git/Github：

[廖雪峰Git教程](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)

[Pro Git中文版](https://git-scm.com/book/zh/v2)

[《Github入门与实践》](http://www.ituring.com.cn/book/1581)

正则表达式：

[30分钟入门正则表达式](http://deerchao.net/tutorials/regex/regex.htm)

[《正则表达式必知必会》](http://www.ituring.com.cn/book/1585)

页面性能优化：

[《高性能网站建设指南》](https://book.douban.com/subject/26411563/)

## 工具

Win平台命令行工具：

[cmder](http://cmder.net/)

[Windows Subsystem Linux](https://msdn.microsoft.com/commandline/wsl/about) （又称Bash On Ubuntu On Windows，该特性需要win10 build 14393之后的版本才能开启）

调试工具：

[Chrome DevTools官方文档](https://developers.google.com/web/tools/chrome-devtools/)

编辑器 & IDE：

Atom，vscode，Sublime Text，Webstorm

CSS 预处理器：

[Sass基础教程](https://www.w3cplus.com/sassguide/)

[Sass指南](https://sass-guidelin.es/zh/#sass)

CSS 后处理器：

[w3cplus的postcss教程](https://www.w3cplus.com/blog/tags/516.html)

ES6 转译器：

[Babel使用指南](http://guoyongfeng.github.io/idoc/html/React%E8%AF%BE%E7%A8%8B%E4%B8%93%E9%A2%98/Babel%E4%BD%BF%E7%94%A8%E6%8C%87%E5%8D%97.html)

前端自动化构建：

[gulp中文官网](http://www.gulpjs.com.cn/)

[gulp基础教程](https://github.com/nimojs/gulp-book)

[npm scripts使用指南 by 阮一峰](http://www.ruanyifeng.com/blog/2016/10/npm_scripts.html)

[如何将npm scripts作为构建工具使用](http://bubkoo.com/2016/03/18/how-to-use-npm-as-a-build-tool/)

文章：[为什么我放弃了gulp和grunt而转投npm scripts](https://medium.freecodecamp.com/why-i-left-gulp-and-grunt-for-npm-scripts-3d6853dd22b8#.274aycdax)

前端打包工具：

webpack: [官方入门指南](https://webpack.js.org/guides/)

rollup: [官方入门指南](http://rollupjs.org/guide/)

## 技术资讯来源

### 邮件订阅

- http://javascriptweekly.com/
- http://html5weekly.com/
- https://web-design-weekly.com/
- http://css-weekly.com/
- http://responsivedesignweekly.com/
- https://www.smashingmagazine.com/

### 微信公众号

- 前端外刊评论（FrontendMagazine）
- 奇舞周刊
- 前端之巅（frontshow）

### 网站

- https://realtime.jser.info/ （JS技术新闻聚合网站）
- https://www.youtube.com/ (很多值得关注的技术频道)
- http://codepen.io/ (前端在线playground)
- http://devdocs.io/ (编程语言、流行框架、库的api聚合查阅工具)
- https://css-tricks.com/ （CSS技巧）
