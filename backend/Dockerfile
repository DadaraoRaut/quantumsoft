FROM eclipse-temurin:23-jdk-alpine
# Set the
WORKDIR /app
# Copy the jar file into the container
COPY target/QuantomSoft-0.0.1-SNAPSHOT.jar QuantomSoft-0.0.1-SNAPSHOT.jar

# Make the port available to the outside world
EXPOSE 8080

# Run the jar file
CMD ["java", "-jar", "QuantomSoft-0.0.1-SNAPSHOT.jar"]

