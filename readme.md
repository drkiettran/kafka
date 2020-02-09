# Apache Kafka with Spring Boot 2.2.4 Project
This is a sample project uses producer & consumer as part of Kafka application.

## build
```
mvn clean package

```

If you run into errors in unit test, try `-Dmaven.test.skip=true`

## run
```
mvn clean spring-boot:run

```

Or

```
mvn clean package
java -jar target/kafka-1.0.0-SNAPSHOT.jar
```