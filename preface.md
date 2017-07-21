# 前言

本来，手机的wap我是不看好的，但是随着微信的流行，很多的wap(h5)应用也随时流行了。
例如：微店，微站。

手机的硬件特点是：

- 硬件设备太差。同主频性能往往是台式机的10分之一
- 网络速度太差。4g网络达到200k/s就不错了，而且往往很不稳定。

所以，传统的web技术，往往在手机端的表现特别差，因为传统技术的特点是：

- 页面整体刷新。
- js/css 的请求往往很多，过百是很常见的事儿。

每次页面整体刷新，都要导致浏览器重新加载对应的内容。特别卡顿。
另外，加载的内容也很多。很多传统页面的css/js 都多达上百个，每次打开页面，
需要发送上百次请求。

在ios机器上还好，ios的速度很快，android机则大部分都很慢。

所以，单页应用（Single page app )则体现出了巨大的优势：

- 局部刷新，响应速度快, 不需要每次都加载所有的js/css,
- 前后端分离，不受开发语言限制。

所以越来越多的app采用了 SPA框架。

如果你的项目要用在h5上，那么一定使用单页应用框架。

Angular, React, Vuejs都是很好的框架。

我们在项目中，都使用Vuejs.



本文跟官方文档不同。是根据实际项目经验，以 培养新人的角度来写的，所以会有这样的
特点：

- 我认为“很少使用的技术“， 略过
- 只讲解最常见的知识。
- 在章节上，按照入门的难易度从简单到复杂。

学习的时候，务必要有个环境，看一点儿文档，就动手敲一敲代码。
否则光看是看不懂的。