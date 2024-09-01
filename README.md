﻿《课程管理平台》是一个典型的前后端分离项目，使用Vue.js作为前端框架和Spring Boot作为后端框架。这个项目旨在帮助新手理解前后端分离的概念，并通过实践来掌握Vue.js和Spring Boot的基本使用方法。

项目录屏：https://www.bilibili.com/video/BV1Kj411L7CG

1. **课程管理模块**：
   - **功能**：允许管理员添加、编辑、删除和查看课程信息。
   - **前端**：使用Vue.js创建课程列表，表单用于输入课程信息，以及按钮进行操作。
   - **后端**：Spring Boot提供RESTful API，处理课程数据的增删改查（CRUD）操作。
2. **作业题目模块**：
   - **功能**：教师可以为课程创建、编辑和发布作业题目，学生可以查看和提交作业。
   - **前端**：Vue.js用于展示作业列表，表单用于教师输入作业题目，学生提交作业。
   - **后端**：Spring Boot处理作业题目的存储和检索，以及学生作业的提交和评分。
3. **考试阅卷模块**：
   - **功能**：教师可以创建考试，学生参加考试，教师进行阅卷和评分。
   - **前端**：Vue.js实现考试界面，学生可以在线答题，教师可以查看学生答案并评分。
   - **后端**：Spring Boot管理考试数据，包括题目、答案和评分，以及考试的发布和结果处理。
4. **教师评价模块**：
   - **功能**：学生可以对教师进行评价，管理员可以查看评价结果。
   - **前端**：Vue.js提供评价表单，学生可以填写评价内容，管理员可以查看评价汇总。
   - **后端**：Spring Boot存储评价数据，提供评价的查询和统计功能。

### 技术栈和工具

- **前端**：
  - **Vue.js**：用于构建用户界面，提供响应式和组件化的开发方式。
  - **Vuex**：状态管理库，用于管理应用的全局状态。
  - **Vue Router**：Vue.js的路由管理器，用于页面导航和组件重用。
  - **Axios**：用于前端与后端的HTTP通信。
- **后端**：
  - **Spring Boot**：简化了Spring应用的初始搭建以及开发过程。
  - **Spring Data JPA**：用于数据库操作，提供简化的数据库访问层。
  - **Spring Security**：用于实现认证和授权。
  - **JWT (JSON Web Tokens)**：用于安全的用户认证和信息交换。
- **数据库**：
  - **MySQL**：关系型数据库，用于存储课程、作业、考试和评价数据。
- **开发工具**：
  - **Visual Studio Code**：前端和后端代码编辑器。
  - **IntelliJ IDEA**：后端开发IDE。
  - **Postman**：用于测试API。

### 学习目标

通过这个项目，新手可以学习到：

- 如何使用Vue.js构建单页面应用（SPA）。
- 如何使用Spring Boot开发RESTful API。
- 如何实现前后端分离的架构。
- 如何进行数据库设计和操作。
- 如何实现用户认证和权限控制。

这个项目不仅有助于理解前后端分离的概念，还能通过实际操作来加深对Vue.js和Spring Boot框架的理解。