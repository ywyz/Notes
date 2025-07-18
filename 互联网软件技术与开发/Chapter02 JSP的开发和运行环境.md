#### （一）JSP的开发和应用平台介绍

#####  识记：

###### ①JSP的开发和应用平台的种类；

首先必须准备一个符合Servlet 2.1/2.2和JSP 3.0或更高规范的开发环境。

还要安装一个支持Java Servlet的Web服务器。

###### ②各平台的特性。

Resin的特性包括以下方面：

支持JSP和在服务器端编译的JavaScript。

比mod_perl、mod_php更快，比Tomcat快3倍。

自动的Servlet/Bean编译。

支持Servlet、XSL Filtering。

支持IIS、Apache、Netscape和其他内置了HTTP/1.1的Web服务器。

XSLT和XPath1.0引擎。企业级的共享软件（基于一个开放源码的协议）。



Tomcat是Servlet 2.2和JSP 1.1规范的官方参考实现。

Tomcat既可以单独作为小型Servlet、JSP测试服务器，也可以继承Apache Web服务器。

直到2000年，Tomcat还是唯一支持Servlet 2.2和JSP 1.1规范的服务器，但现在已经有许多其他服务器宣布对这方面的支持。



BEA公司的WebLogic平台是一个基于Java的功能强大的电子商务套件，它提供了许多功能强大的中间件，以方便编程人员编写JSP、Servlet等电子商务应用，可以为企业提供一个完整的商务应用解决方案，是为超大型电子商务应用系统而设计的。

它采用CORBA（公共对象）的系统结构，提供基于分布式的JSP应用系统。



基于Java和Servlet的Web应用程序运行环境，包含为Web站点提供服务所需要的一切，如项目管理、连接数据库、Java Servlet代码生成器、Bean和Servlet开发工具、HTML编译器、网站发布等，为开发Servlet和Java Bean提供了多种向导。WebSphere Performance Pack作为网络优化管理工具，可以减少网络服务器的拥挤现象，扩大容量，提高Web服务器性能。

运行时可以协同并扩展Apache、Netscape、IIS和IBM的HTTP Web服务器，因此可以成为强大的Web应用服务器。

包含eNentworkDispatcher、WebTrafficeExpress代理服务器和AFS分布式文件系统，可以提供伸缩的Web服务器环境。其基本工作过程是：客户发出请求后，由Http Server将Servlet调用请求交给Application Server，由Application Server和Java Servlet Engine执行用户调用的Servlet进行数据库连接，将SQL请求发送给数据库进行处理；数据库将结果返回Application Server；Servlet生成动态页面后，将处理结果交给Http Server，Http Server将页面返回给用户。由于Websphere面向专业人员，所以要完全掌握的话有一定的难度

####  （二）Eclipse Java EE 集成开发环境 

##### 识记：

###### ①开发环境的定义；

SP开发环境主要包括JavaBean和Servlet等Java类的开发环境与JSP页面的开发环境，Java类的编译需要JDK的支持。

###### ②JDK的配置；

###### ③Tomcat服务器的概述、特点；

Tomcat服务器是开放源代码的Web应用服务器，是目前比较流行的Web应用服务器之一。

Tomcat技术先进、性能稳定，而且免费。

Tomcat运行时占用的系统资源小，扩展性好，支持负载平衡与邮件服务等开发应用系统常用的功能；

实现了对于Servlet 3.0、JSP 2.2和EL 2.2等特性的支持。

Web应用内存溢出侦测和预防；增强了管理程序和服务器管理程序的安全性；

一般CSRF保护；

支持Web应用中的外部内容的直接引用；

重构（Connectors，Lifecycle）及很多核心代码的全面梳理。

######  ④Tomcat 的安装、安装文件夹、解压缩版安装说明；

###### ⑤Tomcat的部署和访问网页的链接；

###### ⑥EclipseJaveEE 开发环境的配置和开发。 

Eclipse Java EE作为一款Java的开发集成软件，拥有即时编译和运行便捷等特性，是开发Java类代码的方便利器。

##### 领会：

###### ①Tomcat的目录结构以及具体内容。 

bin、conf、lib、logs、temp、webapps、work等子目录

1）bin目录。主要存放Tomcat的命令文件。

（2）conf目录。存放Tomcat的配置文件，如server.xml和tomcat-users.xml。server.xml是Tomcat的主要配置文件，其中包含Tomcat的各种配置信息，如监听端口号、日志配置等。如果要修改Tomcat默认的端口号8080，找到如下这段代码即可更改。

（3）logs目录。存放日志文件。

（4）temp目录。主要存放Tomcat临时文件。

（5）webapps目录。存放应用程序实例，待部署的应用程序保存在此目录。

（6）work目录。存放JSP编译后产生的class文件。

####  （四）其他JSP开发环境。

#####  识记：

###### ①JSP的相关开发环境的种类

 IDEA开发环境

Adobe Dreamweaver

UltraEdit编辑器