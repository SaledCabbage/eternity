#eternity

> eternity 
	n.	永恒; 不朽; [宗] 来世，永生，永劫; 万年;

生活也好，爱情也好， 愿我们人生永远也不冷场。

生活应当保持无尽的劲头，

爱情应当保持永恒的执着，

人生应当永不冷场。

一路跌跌撞撞，一生忙忙碌碌，但是总有些东西是要铭心刻骨，总有些东西给我们快乐，让我们铭记。

因此此项目仅仅是本人业余时间做的一些小项目的集合，陆续开发中……

项目地址: http://zhuangjingyang.com:3000/eternity

##包含项目

* [Love Record](https://github.com/iamjohnnyzhuang/LoveRecord)
一个照片轮播的动画网站，纪录了我们在一起的时间。轮播背景用我、她、我们的照片运用上素描大师的滤镜营造故事效果，并且每张图片配上那么一两句话，描述时间地点等信息。

  **迁移至eternity新特性:**
  
  由于之前托管在github pages上，因此只能存放纯静态文件，导致不得不将很多图片地址以及文字硬编码在代码中，非常不利于长久的维护。因此在自己的VPS搭建了Node JS服务器。为什么用Node Js呢，因为足够轻量， Node Js + Express框架非常轻量的搭建了我的项目，连数据库都没有单纯的读写文件，够轻量吧？
  
  借助Node Js服务器，改善了代码的冗余度，方便后期开发维护。
  同时增加了管理员页面(需要账号密码哦):
  http://zhuangjingyang.com:3000/eternity/admin
  
  这样，可以在图形界面上轻松的上传新的图片以及文字了~


* 其他项目陆续开发中...
