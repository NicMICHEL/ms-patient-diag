FROM openjdk:21
ADD target/gateway-ms-0.0.1-SNAPSHOT.jar gateway-ms.jar
EXPOSE 9004
ENTRYPOINT [ "java", "-jar","gateway-ms.jar" ]