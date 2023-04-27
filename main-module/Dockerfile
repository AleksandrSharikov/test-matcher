FROM openjdk:19

ARG JAR_FILE=target/*.jar

RUN mkdir /opt/main

COPY ${JAR_FILE} /opt/main/main-module.jar

ENTRYPOINT ["java","-jar","/opt/main/main-module.jar"]