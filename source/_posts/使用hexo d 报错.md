---
title: 使用hexo d 报错
categories:
  - Hexo
tags:
  - hexo报错
  - 建站经验
date: 2018-11-13 17:49:33
cover_picture: https://s1.ax1x.com/2018/11/13/iObz90.jpg
top: 1
---
### 使用hexo d 提示You should configure deployment settings in _config.yml first!
##### 问题: 使用hexo d 提示You should configure deployment settings in _config.yml first!
##### Available deployer plugins:
##### git

##### For more help, you can check the online docs: http://hexo.io/
### 解决问题:
##### 1.排查->是否安装一下hexo-deployer-git这个模块没有安装:npm install hexo-deployer-git --save使用指令安装
##### 2.排查->_config.yml 这个文件的deploy写了没有;写全了没有我的就是因为_config.yml中deploy下的type等前面没有空格导致。。。。。

##### 以下为正确的写法(图片):
![iObz90.jpg](https://s1.ax1x.com/2018/11/13/iObz90.jpg)

作者：[司徒静峰][1]


 


  [1]: https://www.sitwo.cn/