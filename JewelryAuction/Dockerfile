FROM openjdk:17-jdk-alpine
WORKDIR /app
COPY target/*.jar JewelryAuction.jar
EXPOSE   8080
ENTRYPOINT ["java","-jar","JewelryAuction.jar"]