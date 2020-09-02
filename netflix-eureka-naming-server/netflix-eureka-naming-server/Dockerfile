FROM openjdk:14
ADD target/eureka-naming-server.jar eureka-naming-server.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","eureka-naming-server.jar"]