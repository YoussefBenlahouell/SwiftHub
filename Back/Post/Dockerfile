FROM openjdk:17
WORKDIR /app
COPY target/Post-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8070
ENTRYPOINT ["java", "-jar", "app.jar"]
