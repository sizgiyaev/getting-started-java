FROM openjdk:8u151-jre-alpine

ARG JAR_FILE

ADD $JAR_FILE /opt/helloworld/

CMD ["java", "-jar", "/opt/helloworld/${JAR_FILE}"]