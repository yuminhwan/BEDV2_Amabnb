FROM --platform=linux/x86_64 eclipse-temurin:17-jre-alpine
COPY amabnb-1.0.1.jar app.jar
ENTRYPOINT ["java","-jar", "-Duser.timezone=Asia/Seoul","app.jar"]
