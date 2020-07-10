#Dockerfile for service-app

FROM openjdk11
EXPOSE  8080
#COPY ./target/service-app-0.0.1-SNAPSHOT.jar app.jar

ADD target/service-app-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-jar","app.jar"]
