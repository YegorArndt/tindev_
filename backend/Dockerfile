FROM openjdk:8-jdk-alpine
COPY . /backend
WORKDIR /backend
RUN . /backend ./mvnw clean install
EXPOSE 8080
CMD ["java", "-jar", "target/backend-0.0.1-SNAPSHOT.jar"]