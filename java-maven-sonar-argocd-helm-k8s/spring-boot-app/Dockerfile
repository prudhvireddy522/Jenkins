FROM openjdk:11-jre-slim
WORKDIR /opt/app
COPY target/*.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]
