# TextProducer

TextProducer is a Spring Boot microservice that serves as a producer for Apache Kafka, allowing seamless integration with Kafka clusters. This microservice is developed using Gradle for build automation and Docker for containerization, ensuring easy deployment and scalability.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Ensure you have the following software installed on your local machine:

- Docker
- Java Development Kit (JDK)
- Gradle

### Installation

1. Clone the repository:

```bash
git clone https://github.com/mustafaguc/text-producer.git
```

Navigate to the project directory:
```bash
cd text-producer
```


Build the microservice with Gradle:
```bash
 ./gradlew assemble
```

Build the Docker image:
```bash
docker build -t text-producer .
```
Run the Docker container:
```bash
docker run -d -p 8080:8080 text-producer
```

The microservice will now be accessible at http://localhost:8080.

License
This project is licensed under the MIT License - see the LICENSE file for details.
