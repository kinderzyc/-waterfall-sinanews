# 瀑布流新闻网站
---
## 预览地址：http://jsbin.com/ruguwuvomo/edit?html,output
# 懒加载原理
---
懒加载预览： https://ouyangbeibei.github.io/project/layout.md/lazyLoad.md/lazyLoad.html
> 原理：先将img标签中的src链接设为同一张图片（空白图片），将其真正的图片地址存储再img标签的自定义属性中（比如data-src）。当js监听到该图片元素进入可视窗口时，即将自定义属性中的地址存储到src属性中，达到懒加载的效果。这样做能防止页面一次性向服务器响应大量请求导致服务器响应慢，页面卡顿或崩溃等问题。XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX



