FROM openjdk:11
ADD target/email-producer.jar email-producer.jar
EXPOSE 9091
ENTRYPOINT ["java", "-jar", "email-producer.jar"]
