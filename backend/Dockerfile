FROM eclipse-temurin:21-jre-alpine

WORKDIR /app

# Copy Spring Boot executable JAR produced by Gradle
COPY build/libs/*.jar app.jar

# Expose default HTTP port
EXPOSE 8080

# Run the packaged application
ENTRYPOINT ["java", "-jar", "app.jar"]
