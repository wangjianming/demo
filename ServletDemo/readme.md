1. 首选是tomcat版本下载，选最新版本9.0，现在多了一个embedded版本（可能类似于jetty那样可以嵌入在java代码中控制启停的），选用Core: 64-bit Windows
----后来发现选了9.0 M1版本起不来，原因未知，换8.0就好了
2.  下来选java版本，本机有个jdk 1.7
3.  设置环境变量
set JAVA_HOME=E:\Program Files\Java\jdk1.7.0_67
set PATH=%JAVA_HOME%\bin;%PATH%
set CATALINA_HOME=G:\soft\dev\tomcat\apache-tomcat-8.0.30

4.找一个java的demo，放到tomcat目录，并重启tomcat
G:\soft\dev\tomcat\apache-tomcat-8.0.30\webapps