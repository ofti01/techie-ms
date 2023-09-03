
#use an official java image
FROM openjdk:17-alpine

#Set working directory in the container
WORKDIR /app

#copy the jar file to the container
COPY /home/runner/work/techie-ms/techie-ms/discovery-service/target/discovery-service-0.0.1-SNAPSHOT.jar app.jar

# Set the command to run the JAR file
CMD ["java", "-jar", "app.jar"]