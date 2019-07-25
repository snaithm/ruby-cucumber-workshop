# Ruby Cucumber Workshop
A workshop to write cucumber tests using an existing api hosted in a docker container

### Background - The Customer Api

The customer api offers the following functionality which requires cucumber tests

Create a user - Post - http://localhost:8080/rest-api/api/user/

``` bash
{
	"name":"Kelly Williams",
	"age": 65,
	"salary": 22000
}
```

Search for a user - Get - http://localhost:8080/rest-api/api/user/{userId}

Search for all users - Get - http://localhost:8080/rest-api/api/user/

Delete a user - Delete - http://localhost:8080/rest-api/api/user/{userId}

Delete all users - Delete - http://localhost:8080/rest-api/api/user/

### Getting Started

The api requires java 8 and maven installed

To build the java archive, from the spring-boot-rest-api module

``` bash
mvn clean install
```

To run the service, from the root directory

``` bash
docker-compose up --build
```
