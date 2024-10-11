FROM openjdk:21-slim-buster

LABEL authors="Felipe Q."

WORKDIR /app

COPY target/*.jar app.jar

ENV server_port=8080

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]

#Comando para rodar no terminal:
#docker build -t felipeque/hello-docker:0.1 .
