# 前言

欢迎来到基于微信小程序的学生宿舍管理系统项目。本项目旨在通过微信小程序为载体，实现便捷、高效的学生宿舍管理功能，为广大学生和宿管人员提供优质服务。以下是对本项目的一些详细介绍。

# 内容介绍

本项目主要包括以下功能模块：宿舍基本信息管理、宿舍人员管理、报修管理、卫生管理、用电管理、门禁管理等。通过微信小程序，学生可以随时随地查询宿舍信息、提交报修申请、查看卫生情况等，宿管人员可以方便地处理各项事务，提高工作效率。

# 技术介绍

## 语言：Java

## 使用框架：Spring Springmvc，mybatis，微信小程序

## 前端技术：JS、Vue 、css3，Uniapp

## 开发工具：IDEA/Eclipse，Uniapp

## 数据库：MySQL 5.7/8.0

## 数据库管理工具：phpstudy/Navicat

## JDK版本：jdk1.8

## Maven: apache-maven 3.8.1-bin

## 前端环境：Node.Js 12\14\16

# 核心代码

以下是本项目中的一个核心代码片段，展示了如何通过微信小程序调用后端API获取宿舍列表：

```javascript
// 微信小程序页面
Page({
  data: {
    dormitoryList: []
  },
  onLoad: function(options) {
    this.getDormitoryList();
  },
  getDormitoryList: function() {
    var that = this;
    wx.request({
      url: 'https://your-backend-api/getDormitoryList',
      method: 'GET',
      success: function(res) {
        if (res.data.status === 'success') {
          that.setData({
            dormitoryList: res.data.data
          });
        }
      }
    });
  }
});
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/330171/35/13085/82699/68c6338eF33797ad4/a3d3cfe3e7b71454.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/332370/3/12677/12130/68c63366F6f7ed620/6e86208c058046ae.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/329647/8/13141/12572/68c63366F03881982/f0074942cd5e9040.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/342911/9/3198/27816/68c63367Fd69ba0db/69d65bdf33f6e1ea.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/351140/24/3155/24036/68c63367Fd1794a3a/09eff1fca280d881.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/343905/2/3286/30160/68c63368F1bec1da6/57fd54a659b107d2.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/340454/38/8089/19268/68c63368F43f2e12b/829f2bcc6262d1c5.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326858/13/19964/17658/68c63368F225000ca/897f378370fa0798.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326146/30/19591/12427/68c63369F19bf15b4/8ecb51186fd9954b.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327637/26/19821/22990/68c63369F84e82bbe/f139965124c60087.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
