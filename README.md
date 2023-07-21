# Library-web
Introduction to Database Systems Course (COMP130010.03, 2022 Spring) Project of Fudan University.

这是一个图书管理系统的静态网页版，该项目为复旦大学2022年春《数据库引论》的课程作业。为方便访问且省去服务器的搭建，这里删去了后端和数据库，将JSP重构为HTML，仅进行前端页面的展示。

## 项目结构

```
- css/            存放样式文件的文件夹
- fonts/          存放字体文件的文件夹
- js/             存放JavaScript文件的文件夹
- public/         存放公共资源文件的文件夹
- reader/         读者模块相关文件夹
- 404.html        404页面文件
- 404.jpg         404页面背景图片
- README.md       项目说明文件
- index.html      网站首页文件
- readerLogin.html    读者登录页面文件
```

## 使用方法

1. 在浏览器中打开网站链接 https://librarie.netlify.app/，即可查看网页。
2. 首页 (`index.html`) 用于网页链接初始化。
3. 读者登录页面 (`readerLogin.html`) 允许读者进行登录操作，账户为【reader】，密码为【123456】。
4. 404 页面 (`404.html`) 是一个错误页面，当访问不存在的页面时会显示该页面。

## 注意事项

- 该项目为静态网页版，只提供了前端页面和相关资源文件，不包含后端服务器或数据库。
- 加入后端和数据库的完整版本可参考[https://gitee.com/mingyuefusu/tushuguanlixitong](https://gitee.com/mingyuefusu/tushuguanlixitong)，Library-web也是在该Gitee项目基础上进行修改而来。
