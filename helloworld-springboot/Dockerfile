FROM tomcat:8-jre8

ARG JAR_FILE

ADD $JAR_FILE /opt/helloworld/

CMD ["java", "-jar", "/opt/helloworld/${JAR_FILE}"]