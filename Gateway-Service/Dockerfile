FROM openjdk:18-ea-1-jdk-oracle

VOLUME /tmp
COPY target/Gateway-Service-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java", "-jar" , "app.jar"]

