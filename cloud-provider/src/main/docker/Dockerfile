# 基于哪个镜像
FROM java:8

# 拷贝文件到容器
ADD cloud-provider-0.0.1-SNAPSHOT.jar app.jar

# 微服务项目的启动端口
EXPOSE 8080

# 配置容器启动后执行的命令
ENTRYPOINT  ["java","-jar","/app.jar"]