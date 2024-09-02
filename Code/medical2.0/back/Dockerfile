
FROM openjdk:8-jdk

ADD target/gserver-1.0.0-SNAPSHOT.jar app.jar

EXPOSE 7016

ENV JAVA_OPTS=""

ENTRYPOINT exec java $JAVA_OPTS -jar app.jar
