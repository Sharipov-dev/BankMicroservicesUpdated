#Start with a base image containing Java runtime
FROM openjdk:17-jdk-slim

#Information around who mantains the image
MAINTAINER sharipov

#Add the application's jar to the image
COPY target/cards-0.0.1-SNAPSHOT.jar cards-0.0.1-SNAPSHOT.jar

#Execute the application
ENTRYPOINT ["java", "-jar", "cards-0.0.1-SNAPSHOT.jar"]