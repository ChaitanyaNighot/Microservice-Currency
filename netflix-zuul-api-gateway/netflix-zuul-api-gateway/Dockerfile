FROM openjdk:14
ADD target/zuul-api-gateway.jar zuul-api-gateway.jar
EXPOSE 8765
ENTRYPOINT ["java","-jar","zuul-api-gateway.jar"]