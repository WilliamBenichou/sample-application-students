FROM openjdk:11-jre
ENV MYAPP_HOME /opt/myapp
COPY ./target/*exec.jar $MYAPP_HOME/db.jar

EXPOSE 5432

ENTRYPOINT java -jar db.jar
