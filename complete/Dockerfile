# Use lightweight Java runtime
FROM eclipse-temurin:17-jre

# App directory inside container
WORKDIR /app

# Copy JAR into container
COPY build/libs/*.jar app.jar

# Expose app port
EXPOSE 8080

# Run Spring Boot
ENTRYPOINT ["java", "-jar", "app.jar"]