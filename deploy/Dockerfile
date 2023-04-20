FROM java:openjdk-8-jre-alpine

WORKDIR /home

COPY target/*.jar /home

ENTRYPOINT  ["/bin/sh","-c","java -jar *.jar"]
