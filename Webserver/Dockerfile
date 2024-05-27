FROM openjdk:17-jdk-slim
COPY ./build/libs/Webserver.jar /app/app.jar
ENTRYPOINT ["java", "-jar", "app/app.jar"]