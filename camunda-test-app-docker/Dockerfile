FROM camunda/camunda-bpm-platform:tomcat-latest
MAINTAINER Abhishek Shekhar <abhishek12355@gmail.com>

ENV JPDA_ADDRESS 5005
EXPOSE 5005

ADD target/camunda-test-war1-1.0-SNAPSHOT.war /camunda/webapps/
ADD target/camunda-test-war2-1.0-SNAPSHOT.war /camunda/webapps/