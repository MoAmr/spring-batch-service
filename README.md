# Creating a Spring Batch Service:

This guide walks you through the process of creating a basic batch-driven solution.

## What you will build?

You will build a service that imports data from a CSV spreadsheet, transforms it with custom code, and stores the 
final results in a database.

## Build an executable JAR:

You can run the application from the command line with Gradle or Maven. You can also build a single executable JAR file
that contains all the necessary dependencies, classes, and resources and run that. Building an executable jar makes it 
easy to ship, version, and deploy the service as an application throughout the development lifecycle, across different 
environments, and so forth.

* If you use Gradle, you can run the application by using ```./gradlew bootRun```.
Alternatively, you can build the JAR file by using ```./mvnw clean package``` and then run the JAR file, as follows:
```java -jar build/libs/gs-batch-processing-0.1.0.jar```

* If you use Maven, you can run the application by using ```./mvnw spring-boot:run```.
Alternatively, you can build the JAR file with ```./mvnw clean package``` and then run the JAR file, as follows:
```java -jar target/gs-batch-processing-0.1.0.jar```

## References:
[Creating a Batch Service](https://spring.io/guides/gs/batch-processing/#scratch)