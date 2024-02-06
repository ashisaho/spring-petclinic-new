# Use official OpenJDK base image
FROM openjdk:11-jre-slim

# Set the working directory in the container
WORKDIR /app

# Copy the packaged JAR file into the container at /app
COPY target/spring-petclinic.jar /app/spring-petclinic.jar

# Expose the port that the Spring PetClinic application runs on
EXPOSE 8080

# Run the Spring PetClinic application when the container launches
CMD ["java", "-jar", "spring-petclinic.jar"]