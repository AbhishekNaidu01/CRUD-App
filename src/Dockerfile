
FROM openjdk:17-jdk-slim
WORKDIR /app
COPY . /app

RUN chmod +x mvnw
RUN ./mvnw clean package -DskipTests && ls -l target/

EXPOSE 8080
CMD ["java", "-jar", "target/crud-app-0.0.1-SNAPSHOT.jar"]
