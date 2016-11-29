# ask
一个基于Nodejs的问答平台

# 项目需求
说明：程序员能够在一起讨论技术是一件多么幸福的事情，因此需要开发一个问答平台供技术人员讨论问题，功能需求如下

1. 用户注册页面
2. 用户登陆页面
3. 用户信息页面，注册后可以修改自己的相关信息
4. 我的问答页面，用户登陆后可以看到自己提出的问题，并且可以提出新问题
5. 所有问题页面，在所有问题页面呈现所有用户提出的问题
6. 问题详情页面，在问题详情页面呈现该问题及所有用户回答的答案，并且可以提交新的答案
7. 问题搜索功能，可根据关键字搜索相关的问题

# 技术组合说明

* 服务器：Nodejs
* 高速缓存：Redis
* 数据库：mysql + orm
* 服务器端应用引擎：express
* 服务器端模板引擎：ejs
* 前端应用框架：angularjs + bootstrap
* 构建工具：gulp
* 集成开发环境：WebStorm
* 前端包管理工具：bower
* 后端包管理工具：npm

# 运行步骤

1. 安装XAMPP
2. 启动XAMPP自带的Apache服务器和MySQL服务器
3. 使用XAMPP的PHPMyAdmin将ask.sql导入到数据库中
4. 安装Redis
5. 安装Nodejs环境
6. 进入 code 目录并执行命令 npm install
7. 安装 bower
8. 进入 code/public 目录并执行 bower install
9. 进入 code 目录并执行命令 npm start
10. 待服务器启动成功后，可使用浏览器访问 http://localhost:3000


