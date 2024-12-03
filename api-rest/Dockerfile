
FROM openjdk:23-jdk-slim
ARG JAR_FILE=target/api-rest-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} app_api-rest.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app_api-rest.jar"]