# Activité Pratique N°3 - Event Driben Architecture avec KAFKA

## Description
This project demonstrates the use of Spring Cloud Stream with Kafka. It includes various dependencies and configurations to set up a Spring Boot application that interacts with Kafka for messaging.

## Prerequisites
- Java 17
- Maven 3.9.9
- Spring Boot 3.3.4
- Spring Cloud 2023.0.3
- Docker

## Project Structure
- `pom.xml`: Maven configuration file with dependencies and plugins.
- `mvnw.cmd`: Maven wrapper script for Windows.
- `.mvn/wrapper/maven-wrapper.properties`: Properties file for Maven wrapper configuration.
- `docker-compose.yml`: Docker Compose file to set up Kafka and Zookeeper.

## Dependencies
The project includes the following main dependencies:
- `spring-boot-starter-web`
- `spring-cloud-starter-stream-kafka`
- `spring-cloud-stream`
- `spring-cloud-stream-binder-kafka`
- `spring-cloud-stream-binder-kafka-streams`
- `spring-kafka`
- `lombok` (optional)
- `spring-boot-starter-test` (test scope)
- `spring-cloud-stream-test-binder` (test scope)
- `spring-kafka-test` (test scope)

## Build and Run
To build and run the project, use the following commands:

```sh
./mvnw clean install
./mvnw spring-boot:run
```

To start Kafka and Zookeeper using Docker Compose, use the following command:

```sh
docker-compose up
```

## Configuration

The project uses the following configuration files:  
- `application.properties` or `application.yml` for Spring Boot application configuration.
- `.mvn/wrapper/maven-wrapper.properties` for Maven wrapper configuration.
- `docker-compose.yml` for Docker Compose configuration.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author
- [Lee4ral](https://github.com/Lee4real)