FROM openjdk:8-jre-alpine

WORKDIR /app

ADD target/api-service-1.0.0.jar /app/application.jar

EXPOSE 8080 8081

CMD java -jar application.jar