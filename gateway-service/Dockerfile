FROM openjdk:19

ARG JAR_FILE=target/*.jar

RUN mkdir /opt/gate

COPY ${JAR_FILE} /opt/gate/gateway_app.jar

ENTRYPOINT ["java","-jar","/opt/gate/gateway_app.jar"]