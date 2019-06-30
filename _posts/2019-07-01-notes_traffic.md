---
title: "如何让你知道你的文章多受欢迎"
layout: page
categories:
     - 学习笔记

---
### 添加文章访问量功能
第一步：在_includes目录下的head.html中添加：<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>
以下是我修改的图片参考

![](/assets/images/traffichead.png)

第二步：在_includes目录下的footer.html中添加如下代码：<span id="busuanzi_container_site_pv">本站总访问量：<span id="busuanzi_value_site_pv"></span>次</span>
以下是我修改的图片参考

![](/assets/images/trafficfooter.png)

第三步：在_layouts目录下的post.html中添加如下代码：<span id="busuanzi_container_page_pv"> | 访问量：<span id="busuanzi_value_page_pv"></span> 次</span>
以下是我修改的图片参考

![](/assets/images/trafficpost.png)

修改完之后会在页面的左下角出现

![](/assets/images/trafficeffect.png)

你就成功了。