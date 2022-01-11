FROM adoptopenjdk/openjdk11:ubi
EXPOSE 8081
RUN mkdir -p /app/
ADD build/libs/demo-docker-0.0.1-SNAPSHOT.jar /app/demo-docker-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "/app/demo-docker-0.0.1-SNAPSHOT.jar"]
