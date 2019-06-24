---
title: "HTML新标签知多少"
layout: posts
categories: - 学习笔记
tags:
  - html
  - 新标签
---

1.header：页眉

描述了文档的头部区域，于定义内容的介绍展示区域。

（1）只有必要时使用header，大多数情况下，如果只有h1~h6或hgroup，没有其它需要与之组合在一起的伴生内容，就没有必要用header将它包起来。

（2）header与h1~h6元素中的标题是不能互换的，它们都有各自的语义目的。

（3）不能在header里嵌套footer元素或另一个header，也不能在footer或address元素里嵌套header。

（4）header不一定必须包含nav元素，不过在大多数情况下，如果header包含导航性链接，就可以用nav。

------------


2.nav：标记导航

标签定义导航链接的部分。无论哪种情况，应该仅对文档中重要的链接群使用nav。通常用一个ul元素（无序列表）对链接列表进行标记，除非链接是面包屑链接则使用ol元素（有序列表）。

（1）HTML5不允许将nav嵌套在address元素中。

（2）HTML5规范不推荐对辅助性的页脚链接（使用条款，隐私政策等），所以选择用nav。

------------


3.article：文章标记标签

表示文档、页面、应用或网站中一个独立的容器，原则上是可独立分配或可再用的，即聚合。

（1）article可以嵌套在另一个article里面，只要里面的article与外面的article是部分与整体的关系，但是不能将article嵌套在address元素里。

（2）一个article里包含一个或者多个section元素并是不强制性的。

------------


4.section：区块定义标签

表示的是文档或是应用的一个一般的区块，一般是有一组相似的主题的内容。

（1）section不是一个像div一样的通用容器，因为section表达一定的含义，而div则没有任何语义上的含义。

【特别提醒】如何在article和section中作出选择？

你的内容是适合做聚合的一块独立的内容或一个小组件吗？如果是，使用article。否则使用section。这并不是意味着你必须聚合或芬达article内容，只是其内容适合这样做。

------------


5.aside：定义侧栏标签

表示一部分内容与页面的主题并不是有很大的关系，可以独立存在。aside的例子包括抬升式引用、侧栏、新闻站上列出相关文章的连接框、广告、nav元素组（如博客的友情链接）、商业站上相关产品列表。

（1）如果子啊侧栏中使用一个或多个aside（或将其作为侧栏使用），应在HTML中将他们放在页面主要内容的后面。将重要的内容放在前面有利于SEO和提升可访问性。

（2）对于与内容有关的图像（如图表、图形或带有说明文字的插图），使用figure而非aside。

（3）HTML5不允许将aside嵌套在address元素中。

------------


6.footer：页脚标签
与header标签对应的标签，可以放附录、索引、版权页、许可协议等。

（1）footer元素代表嵌套它的最近的article、aside、nluckquote、body、details、fieldset、figure、nav、section或td元素的页脚。只有当它最近的祖先是body时，它才是整个页面的页脚。

（2）不允许在footer里嵌套header或另一个footer。同时，也不能将footer嵌套在header或address元素里。
