---
### 👉作者QQ ：1556708905 微信：zheng0123Long (支持修改、部署调试、定制毕设)

### 👉接网站建设、小程序、H5、APP、各种系统等

### 👉选题+开题报告+任务书+程序定制+安装调试+ppt 都可以做
---

**博客地址：
[https://blog.csdn.net/2303_76227485/article/details/136252149](https://blog.csdn.net/2303_76227485/article/details/136252149)**

**视频演示：
[https://www.bilibili.com/video/BV1Gz421X7dK/](https://www.bilibili.com/video/BV1Gz421X7dK/)**

**毕业设计所有选题地址：
[https://github.com/ynwynw/allProject](https://github.com/ynwynw/allProject)**

## 基于Java+Springboot+Vue的共享单车租赁管理系统(源代码+数据库)128

## 一、系统介绍
本项目前后端分离，本系统分为管理员、操作员、用户三种角色

### 1、用户：
- 注册、登录、单车搜索、单车租赁、停车点查询、新闻浏览、客服咨询、留言反馈、充值、单车租赁管理、单车归还管理、个人中心、个人收藏管理、密码修改
### 2、操作员：
- 注册、登录、停车点管理、单车管理、租赁单车管理、归还单车管理、维修管理、密码修改
### 3、管理员：
- 操作员所有功能、用户管理、操作员、充值管理、车辆类型管理、系统简介管理、站内新闻管理、留言板管理、轮播图管理、客服管理

## 二、所用技术

后端技术栈：

- Springboot
- MybatisPlus
- Mysql

前端技术栈：

- Vue 
- Vue-router 
- axios 
- element-ui

## 三、环境介绍

基础环境 :IDEA/eclipse, JDK1.8, Mysql5.7及以上,Maven3.6, node14

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
### 1、用户
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)

### 2、操作员：
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)

### 3、管理员：
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)
![contents](./picture/picture31.png)
![contents](./picture/picture32.png)
![contents](./picture/picture33.png)
![contents](./picture/picture34.png)
![contents](./picture/picture35.png)
![contents](./picture/picture36.png)
![contents](./picture/picture37.png)
![contents](./picture/picture38.png)

## 五、浏览地址

前台访问地址：http://localhost:8080/springbootptg21/front/index.html
- 用户账号/密码：用户1/123456

后台访问地址：http://localhost:8081/
- 操作员账号/密码：操作员1/123456
- 管理员账号/密码：abo/abo

## 六、部署教程
1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql文件
2. 使用IDEA/Eclipse导入springbootptg21项目，若为maven项目请选择maven，等待依赖下载完成
3. 进入src/main/resources修改application.yml里面的数据库配置
4. src/main/java/com/SpringbootSchemaApplication.java启动后端项目
5. vscode或idea打开admin项目
6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run dev,执行成功后会显示访问地址

