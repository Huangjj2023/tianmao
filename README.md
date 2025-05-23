# 仿天猫商城
迷你天猫商城是一个基于SSM框架的综合性B2C电商平台，需求设计主要参考天猫商城的购物流程：用户从注册开始，到完成登录，浏览商品，加入购物车，进行下单，确认收货，评价等一系列操作。
作为模拟天猫商城系统的核心组成部分之一，采用SSM框架的天猫数据管理后台包含商品管理，订单管理，类别管理，用户管理和交易额统计等模块，实现了对整个商城的一站式管理和维护。

后端页面兼容IE10及以上现代浏览器，Chrome,Edge,Firebox等浏览器表现效果最佳。

# 部署方式
1.项目使用IntelliJ IDEA开发，请使用IntelliJ IDEA的版本控制检出功能，输入“https://github.com/Huangjj2023/tianmao.git”拉取项目即可。
2.项目数据库master分支为MySQL 5.7版本，feature分支为MySQL 8.0及以上版本，请在码云附件上下载SQL文件或者在resources下的sql文件夹中下载sql，并导入到数据库中。
3.使用IDEA打开项目后，在maven面板刷新项目，下载依赖包。（项目jdk为1.8）
4.在IDEA中启动springboot项目即可（run方式或debug方式都行）。
5.账户名和密码详见附件中的sql文件或者在resources下的sql文件夹中的sql文件（前台页面和后台页面账户密码下方有说明）。
6.swagger接口文档地址：http://localhost:8082/tmall/swagger-ui.html
7.Druid Monitor监控地址：http://localhost:8082/tmall/druid/sql.html（账号：admin 密码：123456）

注意事项：后台管理界面的订单图表没有数据为正常现象，该图表显示的为近7天的交易额。

---后台界面(部分)--- 访问地址：http://localhost:8082/tmall/admin/login（账户名和密码在admin表里）
