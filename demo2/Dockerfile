FROM openjdk:11
COPY build/libs/demo-0.0.1-SNAPSHOT.jar app.jar
RUN chmod +x ./gradlew
CMD ["java", "-jar", "app.jar"]
EXPOSE 8081
