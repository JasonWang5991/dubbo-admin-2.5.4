setup 

1. 把这个dubbo-admin-2.5.4.war拷贝到 tomcat下的webapps目录下
 
2. 修改tomcat的端口为8088,修改方法如下，打到conf下的文件 server.xml，因为zookeeper会用到8080的端口，所以为了不冲突，把Tomcat的端口改一下。记得一定要改！！！

3 .先启动zookeeper,然后再启动tomcat,在浏览器输入 http://localhost:8088/dubbo-admin-2.5.4-SNAPSHOT/ 

4. 输入root/root 进入系统


Description

 支持tomcat 1.8 jdk 1.8