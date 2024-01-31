# Spring HTTP Demo

This is a simple Spring Boot application that demonstrates the use of HTTP endpoints.

## Endpoints

The application has the following endpoints:

- `/greeting`: This endpoint accepts a `name` query parameter and returns a greeting message. If no `name` is provided, it defaults to "World".

- `/hello`: Similar to the `/greeting` endpoint, this endpoint also accepts a `name` query parameter and returns a greeting message. If no `name` is provided, it defaults to "World".

## Running the Application

To run the application, you can use the following command in the terminal:

```sh
./mvnw spring-boot:run
```

## Testing the Application

To test the application, you can use the following command in the terminal:

```sh
./mvnw test
```

## Building the Application

To build the application, you need to have [Maven](https://maven.apache.org/download.cgi) installed on your machine. Once you have Maven installed, you can use the following command in the terminal to build the application:

```sh
./mvnw clean install
```

To run the packaged application, you can use the following command:

```sh
java -jar target/springHTTPDemo-0.0.1-SNAPSHOT.jar
```

Now go to `http://localhost:8080/greeting` or `http://localhost:8080/hello`

