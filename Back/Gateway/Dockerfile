FROM openjdk:17
WORKDIR /app
COPY target/Gateway-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8222
ENTRYPOINT ["java", "-jar", "app.jar"]
