FROM openjdk:17
WORKDIR /app
COPY target/User-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8050
ENTRYPOINT ["java", "-jar", "app.jar"]
