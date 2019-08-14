# 简介
本小程序是对王者荣耀用户开发的。后端由Django的restful api搭建，python web服务器为uwsgi，数据库为sqlite,负载均衡、反向代理用的是Ngnix。前端用的是jquery框架。
ps：数据库可以用redis代替提高高并发和实时的性能。
## 小程序功能
小程序主要是将直播间中主播对于英雄的理解显示给大多用户。由于很多人想要知道主播的玩法出装及铭文想出的点子。
## 如何在自己本地部署
小程序用的总体框架是虎牙提供的脚手架(自行查看开发文档)https://github.com/huya-ext/miniapp/wiki/ems
安装完成后，将文件目录替换。
将自己的服务器地址填到js的指定位置



## 修改及加强
就本人自己的观点，web端开发基本完成，pc端半成品有待提高，希望能帮助到有需要的人


