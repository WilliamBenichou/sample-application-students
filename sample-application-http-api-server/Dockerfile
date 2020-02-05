FROM openjdk:11-jre
ENV MYAPP_HOME /opt/myapp
COPY ./target/*exec.jar $MYAPP_HOME/api.jar

EXPOSE 8080

ENTRYPOINT java -jar api.jar
