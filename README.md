# 期末项目
## 非遗商城
### 用萤火商城搭建APP
一. 安装宝塔
1. 商城源码下载（又称后端、服务端，PHP开发 用于管理后台和提供api接口）
2. 上传文件并解压
![Image text](https://github.com/hongzhouxiao/-/blob/main/directory/13.png)
3. 将后端源码上传至服务器站点，并且将站点运行目录设置为/public (删除user.ini)
4. 根据页面提示完成安装

二.创建一个数据库
1. 创建一个数据库,新建网站
!(https://github.com/hongzhouxiao/-/blob/main/directory/13.png)

三.运行网站
### 175.178.226.232/install
!(https://github.com/hongzhouxiao/-/blob/main/directory/12.png)

四. 登录后台
1. 新建商城列表
![输入图片说明](5.png)
2. 创建商品
![输入图片说明](1.png)
3. 编辑主页
![输入图片说明](4.png)

五. 前端调试
1. 打开HBuilderX -> 顶部菜单栏 -> 文件 -> 导入 -> 从本地目录导入 -> 选择uniapp端项目目录
2. 找到config.js文件，找到里面的apiUrl项，填入已搭建的后端url地址
3. 打开manifest.json文件，选择微信小程序配置，填写小程序的appid
![输入图片说明](8.png)

六. 本地调试
1. 打开HBuilderX -> 顶部菜单栏 -> 发行 -> 小程序-微信
![输入图片说明](15.png)
