# 使用 JDK 17 的 OpenJDK 镜像
FROM openjdk:17-jre-slim

# 设置工作目录
WORKDIR /app

# 复制构建好的 JAR 文件到容器中
COPY target/reservation-servcie-1.0-SNAPSHOT.jar reservation-servcie-1.0-SNAPSHOT.jar

# 启动 Reservation Service 应用
ENTRYPOINT ["java", "-jar", "reservation-servcie-1.0-SNAPSHOT.jar"]

# 开放端口 8070
EXPOSE 8070
