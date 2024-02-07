FROM openjdk:17
COPY target/kubeapp-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8081
ENTRYPOINT ["sh", "-c", "java -jar /app.jar"]