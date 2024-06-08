# Use OpenJDK 17 as the base image
FROM openjdk:17-jdk-alpine

# Simplify the artifact path
ARG artifact=target/spring-boot-web.jar

WORKDIR /opt/app

COPY ${artifact} app.jar

# This should not be changed
ENTRYPOINT ["java","-jar","app.jar"]

