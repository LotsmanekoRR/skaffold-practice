# Use the official AdoptOpenJDK for a base image.
# https://hub.docker.com/_/openjdk
FROM openjdk:8-slim
WORKDIR /app
COPY target/demo-0.0.1-SNAPSHOT.jar demo.jar
# Run the web service on container startup.
CMD java -Dserver.port=8080 -jar demo.jar