FROM openjdk:11
COPY "./target/spring-boot-docker-0.0.2.jar" "app.jar"
ENTRYPOINT ["java","-Dspring.data.mongodb.uri=mongodb://test:27017/mongo-on-docker" , "-Djava.security.egd=file:/dev/./urandom","-jar","app.jar"]