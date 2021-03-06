## 前言

前后端分离的开发方式，我们以接口为标准来进行推动，定义好接口，各自开发自己的功能，最后进行联调整合。无论是开发原生的APP还是webapp还是PC端的软件,只要是前后端分离的模式，就避免不了调用后端提供的接口来进行业务交互。

网页或者app，只要抓下包就可以清楚的知道这个请求获取到的数据，这样的接口对爬虫工程师来说是一种福音，要抓你的数据简直轻而易举。

数据的安全性非常重要，特别是用户相关的信息，稍有不慎就会被不法分子盗用，所以我们对这块要非常重视，容不得马虎。

monkey-api-encrypt是对基于Servlet的Web框架API请求进行统一加解密操作的框架。

## 功能点

- 支持所有基于Servlet的Web框架（Spring Boot, Spring Cloud Zuul等框架）
- 内置AES加密算法
- 支持用户自定义加密算法
- 使用简单，有操作示列

## 文档

- [使用文档](https://github.com/yinjihuan/monkey-api-encrypt/wiki/%E4%BD%BF%E7%94%A8%E6%96%87%E6%A1%A3)

- [原理文档](https://github.com/yinjihuan/monkey-api-encrypt/wiki/%E5%8E%9F%E7%90%86%E6%96%87%E6%A1%A3)

- [自定义加密算法](https://github.com/yinjihuan/monkey-api-encrypt/wiki/%E8%87%AA%E5%AE%9A%E4%B9%89%E5%8A%A0%E5%AF%86%E7%AE%97%E6%B3%95)

- [常见问题](https://github.com/yinjihuan/monkey-api-encrypt/wiki/%E5%B8%B8%E8%A7%81%E9%97%AE%E9%A2%98)

## 注意

spring-boot-starter-encrypt是最开始的1.0版本，基于Spring MVC机制实现的，像Zuul中就使用不了，代码留着可以给大家参考下。

示列：https://github.com/yinjihuan/spring-boot-starter-encrypt-example

原理讲解：http://cxytiandi.com/blog/detail/20235


# 作者
- 尹吉欢 1304489315@qq.com
- 博客 http://cxytiandi.com/blogs/yinjihuan
- 技术交流微信群请加我微信拉你进群：jihuan900

更多技术分享请关注微信公众号：猿天地

![image.png](http://upload-images.jianshu.io/upload_images/2685774-da01a73d0cfc3f35.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
