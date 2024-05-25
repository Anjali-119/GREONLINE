# GREONLINE
GrenOnline is a Spring Boot application designed to help users adopt a greener lifestyle by providing information, tips, and resources. The application demonstrates the use of Spring Boot to create a RESTful API along with a simple front-end interface.

Features
User registration and login
Viewing and sharing green living tips
Browsing eco-friendly products
Admin dashboard for managing content
Technologies Used
Java 17
Spring Boot 3.x
Spring Security
Spring Data JPA
H2 Database (for development and testing)
Thymeleaf (for server-side rendering)
Maven (for build and dependency management)
Getting Started
Prerequisites
Ensure you have the following installed on your local machine:

Java Development Kit (JDK) 17 or higher
Maven 3.6 or higher
Installation


grenonline
├── src
│   ├── main
│   │   ├── java
│   │   │   └── com
│   │   │       └── example
│   │   │           └── grenonline
│   │   │               ├── controller
│   │   │               ├── model
│   │   │               ├── repository
│   │   │               ├── service
│   │   │               └── GrenonlineApplication.java
│   │   └── resources
│   │       ├── static
│   │       ├── templates
│   │       ├── application.properties
│   │       └── data.sql
│   └── test
│       └── java
│           └── com
│               └── example
│                   └── grenonline
│                       └── GrenonlineApplicationTests.java
├── mvnw
├── mvnw.cmd
├── pom.xml
└── README.md
controller: Contains the web controllers.
model: Contains the entity classes.
repository: Contains the Spring Data JPA repositories.
service: Contains the service layer classes.
resources/templates: Contains the Thymeleaf templates.
application.properties: Configuration file for the application.
data.sql: Initial data for the H2 database.

