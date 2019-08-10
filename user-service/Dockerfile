FROM openjdk:11
ADD ./target/springbootdemo-0.0.1-SNAPSHOT.jar /springbootdemo-0.0.1-SNAPSHOT.jar
EXPOSE 8087
WORKDIR usr/src
ENTRYPOINT ["java","-jar","springbootdemo-0.0.1-SNAPSHOT.jar"]