##Pull jdk11 from DockerHub
FROM openjdk:11
##Specify the work directory
WORKDIR usr/src
##Add the jar file to be executed
ADD ./target/rabbit-mq-producer-0.0.1-SNAPSHOT.jar /usr/src/rabbit-mq-producer-0.0.1-SNAPSHOT.jar
##ENTRYPOINT allows you to configure a container that will run as an executable
ENTRYPOINT ["java","-jar","rabbit-mq-producer-0.0.1-SNAPSHOT.jar"]
