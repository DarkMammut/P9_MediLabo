FROM openjdk:17-jdk-slim
VOLUME /tmp
COPY target/patient-service-0.0.1-SNAPSHOT.jar app.jar
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar"]
EXPOSE 8080
