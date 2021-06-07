FROM openjdk:11
ADD target/email-consumer.jar email-consumer.jar
EXPOSE 8091
ENTRYPOINT ["java", "-jar", "email-consumer.jar"]
