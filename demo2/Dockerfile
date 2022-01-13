FROM openjdk:11
ENV APP_HOME=/usr/app/
WORKDIR $APP_HOME
COPY . build/libs/*.jar
EXPOSE 8081
CMD ["java", "-jar", "demo-0.0.1-SNAPSHOT.jar"]
