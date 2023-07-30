FROM openjdk:11

EXPOSE 8089

WORKDIR /app
COPY target/github-actions-gke-0.0.2-SNAPSHOT.jar /app/app.jar

CMD ["java", "-jar", "app.jar"]