FROM openjdk:8-jdk-alpine
VOLUME /tmp
EXPOSE 8080
ADD hello-world-rest-api.jar target/hello-world-rest-api.jar
ENTRYPOINT [ "sh", "-c", "java -jar /hello-world-rest-api.jar" ]