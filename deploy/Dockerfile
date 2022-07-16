FROM openjdk:8-jdk-alpine
ARG JAR_FILE=build/libs/*.jar
COPY ${JAR_FILE} amabnb-1.0.1.jar
ENTRYPOINT ["java","-jar", "-Duser.timezone=Asia/Seoul","demo-0.0.1-SNAPSHOT.jar"]
