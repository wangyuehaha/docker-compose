# 基础镜像
FROM java:8

# 复制文件
COPY wy-cms.jar /wy-cms/wy-cms.jar

# 暴露端口，只是声明
EXPOSE 8080

# 容器启动后执行的命令
CMD ["java", "-jar", "/wy-cms/wy-cms.jar"]

