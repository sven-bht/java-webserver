FROM openjdk:17-jdk-slim
COPY ./build/libs/API-Server.jar /app/app.jar
ENTRYPOINT ["java", "-jar", "app/app.jar"]