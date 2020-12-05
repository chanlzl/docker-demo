# 添加 Java 8 镜像来源
FROM openjdk:8-jdk-alpine

VOLUME /tmp

COPY demo-0.0.1-SNAPSHOT.jar demo-1.0.0.jar

#声明运行时容器提供服务端口，这只是一个声明，在运行时并不会因为这个声明应用就会开启这个端口的服务
EXPOSE 8080

#指定容器启动程序及参数   <ENTRYPOINT> "<CMD>"
ENTRYPOINT ["java","-jar","demo-1.0.0.jar"]