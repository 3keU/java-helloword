FROM openjdk:8u102-jre

WORKDIR /home

COPY target/*.jar /home

ENTRYPOINT  ["/bin/sh","-c","java -jar *.jar"]
