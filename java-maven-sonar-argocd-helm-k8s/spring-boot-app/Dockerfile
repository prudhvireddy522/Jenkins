FROM eclipse-temurin:21-jre-jammy
WORKDIR /opt/app
COPY target/*.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]
