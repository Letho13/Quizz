FROM maven:3.9.4-amazoncorretto-21 AS builder

COPY target/user-service-0.0.1-SNAPSHOT.jar user-service.jar

EXPOSE 8081

ENTRYPOINT ["java","-jar","user-service.jar"]