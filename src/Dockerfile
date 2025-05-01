FROM openjdk:17-jdk-slim

WORKDIR /app
COPY . /app

# Make mvnw executable (important for Windows users)
RUN chmod +x mvnw

# Build the project
RUN ./mvnw clean package -DskipTests

EXPOSE 8080

# Run the correct JAR
CMD ["java", "-jar", "target/crudapp-0.0.1-SNAPSHOT.jar"]
