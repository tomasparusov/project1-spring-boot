# Project 1 – Spring Boot MVC Application

## Description
This project was created as part of the Spring Framework assignment (Task 1).
The goal of the project is to build a simple Spring Boot application that demonstrates:
- handling HTTP GET requests
- returning plain text using @ResponseBody
- returning an HTML page using Spring MVC and Thymeleaf

## Technologies
- Java 17
- Spring Boot
- Spring Web
- Thymeleaf
- Maven
- Embedded Tomcat

## How to run the project
1. Open the project in IntelliJ IDEA
2. Run the `Project1Application` class
3. The application will start on port **8080**

## Endpoints

### GET /
- URL: `http://localhost:8080/`
- Description: Returns a simple text response
- Example response:

Hello Spring Boot from Tomas!

### GET /greeting
- URL: `http://localhost:8080/greeting`
- Description: Returns an HTML page rendered with Thymeleaf

## Project structure
src/main/java/com/example/project1
├── Project1Application.java
└── controller
├── HelloController.java
└── GreetingController.java

src/main/resources
└── templates
└── greeting.html

## Summary
This project demonstrates basic Spring Boot functionality including REST controllers,
MVC controllers, and rendering HTML views using Thymeleaf.
