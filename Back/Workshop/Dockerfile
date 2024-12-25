FROM openjdk:17
WORKDIR /app
COPY target/Workshop-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8020
ENTRYPOINT ["java", "-jar", "app.jar"]
