# 1.项目介绍
- 项目角色：管理员、商家、普通用户
- 功能模块：商家管理、用户管理、广告信息管理、美食分类管理、美食信息管理、系统管理、订单管理等
- 技术选型：SpringBoot、vue、uniapp等
- 测试环境：idea2024，jdk8，maven3，微信开发工具，HbuilderX，navicat等
# 2.项目部署
## 2.1 后端部署
- 创建数据库，并导入db下的sql文件
- 通过idea打开项目，根据本地数据库环境配置src/main/resources/application.yml 12-15行
- 启动项目 src/main/java/com/SpringbootSchemaApplication.java
- 管理web：http://localhost:8080/springboot9gk4k/admin/dist/index.html  管理员账号密码：abo/abo， 商家查看shangjia表
- 说明：上述url中的dist是vue项目编译后的，如果你相对前端进行修改，可以通过vscode或者idea安装vue插件，或者webstorm打开src/main/resources/admin/admin 这个是vue项目
## 2.2 小程序部署
- 通过微信开发工具，打开项目project\front\unpackage\dist\dev\mp-weixin
- appid配置为你自己小程序的，或者你自己申请的测试小程序appid
- 信任项目即可，如果页面空白，重新编译下
- 说明：mp-weixin是uniapp项目编译后的，如果你想对小程序做一些修改，你可以 通过HbuilderX打开project\front目录 ，这个是uniapp项目
# 3.项目部分截图
![输入图片说明](1.png)
![输入图片说明](2.png)
![输入图片说明](3.png)
![输入图片说明](4.png)
![输入图片说明](5.png)
![输入图片说明](6.png)
![输入图片说明](7.png)
![输入图片说明](8.png)
![输入图片说明](9.png)
![输入图片说明](91.png)

# 4.获取方式
[戳我查看](https://gitee.com/aven999/mall)
