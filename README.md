MaDe 编辑器
===========

一个可以离线使用的Chrome App Markdown编辑器，MaDe 意为 MArkDown Editor。[Chrome商店地址](https://chrome.google.com/webstore/detail/made/oknndfeeopgpibecfjljjfanledpbkog)。

自从0.8以来多年没有更新过了。在Windows平台经历了Markdown Pad 2、Haroopad这类编辑之后，还是觉得像MaDe这么个简易的浏览器App反而更容易使用。于是根据自己需要稍微做了一些修改：

* 添加纯JS实现的Markdown渲染器[marked](https://github.com/chjj/marked)，因为它支持[Github-Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/)。
* 添加[highlight.js](https://github.com/isagalaev/highlight.js)，为marked增加源码块的语法高亮支持。
* 调整Preview视图的css样式，主要将字体改为更适合渲染中文的微软雅黑，添加了highlight.js所需的github风格样式。
* 在上方控制栏增加了选项开关，可以随时选择渲染引擎是用旧的经典Markdown还是使用GFM风格。并且该选项的状态会被保存到LocalStorage。

开发者下载[MaDe.crx](https://github.com/sinsinpub/MaDe/raw/master/packaged/MaDe.crx)后，拖入Chrome扩展程序的开发者模式下，可以快速安装测试。
