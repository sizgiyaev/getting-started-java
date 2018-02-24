FROM openjdk:8u151-jre-alpine

ARG JAR_FILE

RUN mkdir -p /opt/helloworld

COPY $JAR_FILE /opt/helloworld/app.jar

CMD ["java", "-jar", "/opt/helloworld/app.jar"]