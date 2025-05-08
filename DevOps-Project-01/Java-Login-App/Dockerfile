# Use an official OpenJDK runtime as a parent image
FROM openjdk:11-jre-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the WAR file into the container's /app directory
COPY target/dptweb-1.0.war /app/dptweb-1.0.war

# Expose port 8080 to allow communication to/from the container
EXPOSE 8080

# Define the command to run your application
ENTRYPOINT ["java", "-jar", "/app/dptweb-1.0.war"]


