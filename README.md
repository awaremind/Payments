# Payments

The Payments application is built using Spring Boot. It uses a pre-defined logic to process transations. 

## Running the application

The application can be started up by entering the following command from within the Payments directory

`mvn spring-boot:run`

Alternately, the following command may be executed to build and execute an executable JAR

`mvn clean package`

`java -jar target/Payments-1.0.0-SNAPSHOT.jar`

Once running, the API information and details can be accessed on:
`http://localhost:18081/swagger-ui.html#/payments-controller`

## Application Details

***

## Configuration

In the Spring setup properties, the src/main/resources/application.properties file are specified the following:

`system.payments.transaction=`


## Known Limitation

***
