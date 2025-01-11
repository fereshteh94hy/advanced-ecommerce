FROM eclipse-temurin:21-jdk-alpine

WORKDIR /app

COPY target/*.jar service-registry.jar

EXPOSE 8761

ENTRYPOINT ["java", "-jar", "service-registry.jar"]