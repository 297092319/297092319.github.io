---
title: wamp服务器让局域网用户访问，403forbidden
date: 2019-03-01 11:50:23
categories:
  -服务器
tags: 
  -经验总结
  -建站经验
  -WAMP集成环境
---
1.httpd.conf文件，搜索关键字：onlineoffline tag - don't remove，将 Require local 修改成 Require all granted；

2.httpd-Vhosts.conf 文件，同样将Require local 修改成 Require all granted；（这个是大多数博客没有写的）

3.重启Apache；

4.重点！重点！重点！  关闭防火墙.

![apache][1]

![denfender][2]



[1]: https://s2.ax1x.com/2019/03/01/kH4RQH.png
[2]: https://s2.ax1x.com/2019/03/01/kH4Wyd.png


