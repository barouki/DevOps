FROM openjdk:latest

WORKDIR /spring
COPY spring .
RUN ./mvnw package
CMD java -jar ./target/docker-example-1.1.3.jar
