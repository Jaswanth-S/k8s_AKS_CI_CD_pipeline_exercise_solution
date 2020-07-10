#Dockerfile for service-app

FROM openjdk
EXPOSE  8080

COPY ./target/service-app-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]

