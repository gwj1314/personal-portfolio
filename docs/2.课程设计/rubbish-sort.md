## rubbish-sort

> 基于JSP的垃圾分类科普教育类网站，课程作业

> 最后一次更新：2022.06.01

#### 项目展示

项目地址：http://localhost:8080/rubbish/

1、支持登录注册

会通过JavaBean在右上角记录和显示当前的登录状态。

2、支持关键词搜索

可以在数据库中搜索对应垃圾数据

![search](images/search.png)

3、积分商城

未登录时会提示登录，注册后默认有10积分，可以通过玩游戏或者答题获得积分。

在积分商城兑换商品会扣除对应的积分。

![point](images/point.png)

![game](images/game.png)

![problem](images/problem.png)

#### 项目环境

JDK：Azul15，语言级别SDK15，模块语言级别8

Tomcat 8.5.79

mysql 8.0.12

mysql-connector-java-8.0.28

IDEA

#### 项目运行

数据库信息连接池在\src\main\webapp\META-INF\context.xml中修改

数据表在images中

运行配置，编译两个工件然后构建，部署war工件。

项目设置，在工件的war中，应用程序归档，引入jdbc。

可以将不含源代码的打包后的工件部署到服务器配合tomcat单独运行（成功测试）



