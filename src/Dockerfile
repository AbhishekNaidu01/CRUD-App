# Use official OpenJDK image
FROM openjdk:17-jdk-slim

# Set working directory
WORKDIR /app

# Copy and build your app
COPY . /app
RUN ./mvnw clean package -DskipTests

# Expose port (default Spring Boot port)
EXPOSE 8080

# Run the app
CMD ["java", "-jar", "target/*.jar"]
