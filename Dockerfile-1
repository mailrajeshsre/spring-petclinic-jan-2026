FROM amazoncorretto:17
LABEL project="learning"
LABEL author="Rajesh"
ADD target/spring-petclinic-4.0.0-SNAPSHOT.jar /spring-petclinic-4.0.0-SNAPSHOT.jar
EXPOSE 8080/tcp
CMD ["java", "-jar", "/spring-petclinic-4.0.0-SNAPSHOT.jar"]
