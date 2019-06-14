From openjdk:8

COPY ./employee-consumer-0.0.1-SNAPSHOT.jar employee-consumer-0.0.1-SNAPSHOT.jar
CMD ["java","-jar","employee-consumer-0.0.1-SNAPSHOT.jar"]