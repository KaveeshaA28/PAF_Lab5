# PAF Lab 5 - REST APIs with Spring HATEOAS

## IT3030 Programming Applications and Frameworks 2026

## About
A simple Hypermedia Driven REST API built with Spring Boot and Spring HATEOAS.

## How to Run
1. Clone the repository
2. Open in VS Code
3. Run the application
4. Visit: http://localhost:8080/greeting

## Sample Response
{
  "content": "Hello, World!",
  "_links": {
    "self": {
      "href": "http://localhost:8080/greeting?name=World"
    }
  }
}

## Technologies Used
- Java 17
- Spring Boot 3.5.11
- Spring HATEOAS
- Maven
