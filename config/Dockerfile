FROM openjdk:19

ARG JAR_FILE=target/*.jar

RUN mkdir /opt/config

COPY ${JAR_FILE} /opt/config/config_app.jar

ENTRYPOINT ["java","-jar","/opt/config/config_app.jar"]