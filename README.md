# 前言

随着新冠疫情的不断发展，及时、准确地发布疫情通告成为了抗击疫情的重要手段。基于此，我们开发了“基于SSM的疫情通告系统”，旨在为用户提供一个便捷、高效的疫情信息发布和查询平台。

# 内容介绍

本项目采用Java语言，结合Spring、SpringMVC、MyBatis框架，前端使用JS、Vue、CSS3技术进行开发。系统具有以下功能：

1. 疫情通告发布：管理员可发布疫情通告，包括通告标题、内容、发布时间等。
2. 疫情通告查询：用户可以根据关键词、时间范围等条件查询疫情通告。
3. 用户管理：管理员可以对用户进行增删改查操作，保证系统安全性和稳定性。

# 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

# 核心代码

以下为疫情通告发布功能的部分代码：

```java
// 注解方式实现疫情通告发布
@PostMapping("/publishNotice")
public Result publishNotice(@RequestBody Notice notice) {
    noticeService.publishNotice(notice);
    return Result.success();
}
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

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/325942/28/15178/137919/68b73426Fc8d01d1f/1a235fbcc00f792a.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327010/38/14867/68806/68b733feFfdde8e71/9fc9f623d2ed77e8.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326842/1/15170/56885/68b733feF8ad71ef7/73bf8353c6dfead9.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325606/21/15002/50431/68b733ffF54d1f55b/b8ceb780f35f947c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/337234/27/5803/54146/68b733ffFdbf58cfa/a6bb305599992b31.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337786/28/5701/78007/68b733ffF1024b64f/a5ae2a8100652cd9.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/336232/31/5817/66239/68b733ffFf2fc7f19/3b9920c2789a4e74.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/328831/12/15139/48621/68b73400Fde7dcba9/bf9aa56161eac78f.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/333833/35/8200/72809/68b73400Fd17f8b2d/136912efb6625eb7.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325419/15/15045/39980/68b73401F40070258/2fe4da6727eecd12.jpg)
