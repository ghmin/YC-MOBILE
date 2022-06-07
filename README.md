# YC-MOBILE
yicai的移动端web网站


如何运行？

1、首先请安装配置nodejs v16，然后，进入目录：

cd YC-MOBILE
安装node的依赖：
npm i --registry=https://registry.npm.taobao.org

安装完毕以后，接下来，本机运行方式是：
 ionic serve --host=0.0.0.0 --proxy-config proxy.config.js
 打包方式是：
 ionic build  --engine=browser
 打包以后看到 目录：www就是打包输出结果。

