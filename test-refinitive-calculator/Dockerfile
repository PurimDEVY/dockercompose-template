FROM openjdk:8
VOLUME /tmp
ADD target/calculator-0.0.1-SNAPSHOT.jar calculator-0.0.1-SNAPSHOT.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","calculator-0.0.1-SNAPSHOT.jar"]