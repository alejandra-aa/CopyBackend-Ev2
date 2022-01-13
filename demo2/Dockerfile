FROM openjdk:11
COPY build/libs/demo-0.0.1-SNAPSHOT.jar app.jar
RUN ./gradlew build
CMD ["java", "-jar", "app.jar"]
EXPOSE 8081
