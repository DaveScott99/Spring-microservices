FROM openjdk:17
LABEL authors="Davi Santos"
ARG JAR_FILE=target/*.jar
ADD ${JAR_FILE} app.jar
EXPOSE 8762
ENTRYPOINT ["java", "-jar", "/app.jar"]