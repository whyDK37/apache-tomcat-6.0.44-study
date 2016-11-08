# apache-tomcat-6.0.44-study
整理自 [Snowball](http://blog.csdn.net/yangzl2008/) 的博客。

## 启动
org.apache.catalina.startup.Bootstrap

-Dcatalina.home=catalina-home -Dcatalina.base=catalina-home -Djava.endorsed.dirs=catalina-home/endorsed -Djava.io.tmpdir=catalina-home/temp -Djava.util.logging.manager=org.apache.juli.ClassLoaderLogManager -Djava.util.logging.config.file=catalina-home/conf/logging.properties

org.apache.catalina.util.ServerInfo
 ***
# 参考博客
 - [Tomcat源码阅读系列（一）使用IntelliJ IDEA运行Tomcat6源码](http://blog.csdn.net/yangzl2008/article/details/43982747)
 - [Tomcat源码阅读系列（二）Tomcat总体架构](http://blog.csdn.net/yangzl2008/article/details/44784133)
 1. [CopyOnWriteArrayList与Collections.synchronizedList的性能对比](http://blog.csdn.net/yangzl2008/article/details/39456817)
 - [Tomcat源码阅读系列（三）启动和关闭过程](http://blog.csdn.net/yangzl2008/article/details/45398643)
 1. [查看tomcat启动文件都干点啥](http://www.cnblogs.com/fantiantian/p/3620022.html)
 2. [查看tomcat启动文件都干点啥---catalina.bat](http://www.cnblogs.com/fantiantian/p/3623740.html)
 - [Tomcat源码阅读系列（四）Connector连接器](http://blog.csdn.net/yangzl2008/article/details/46225031)
 - [Tomcat源码阅读系列（五）Catalina容器](http://blog.csdn.net/yangzl2008/article/details/46686765)
 - [Tomcat源码阅读系列（六）类加载器](http://blog.csdn.net/yangzl2008/article/details/48214945)
 - [Tomcat源码阅读系列（七）Session管理机制](http://blog.csdn.net/yangzl2008/article/details/48219129)
 - [Tomcat源码阅读系列（八）设计模式](http://blog.csdn.net/yangzl2008/article/details/48221411)