# Pattern-Grid-Authetication
Pattern Grid Authentication System Project ReadMe
Project Description
This repository contains a Java application that implements a Pattern Grid Authentication System using Java, SQL, and Spring Boot. The Pattern Grid Authentication System is a security mechanism that allows users to authenticate by drawing a pre-defined pattern on a grid.

Project Features
User Registration: Users can create an account by providing their username and setting a pattern for authentication.
User Authentication: Users can log in by drawing their pre-defined pattern on the grid.
Pattern Management: Users can change their authentication pattern.
Security: The application ensures the security of user credentials and pattern data.
Technologies Used
Java: The core programming language for building the application.
SQL: Used to store user account information, including usernames and authentication patterns.
Spring Boot: A framework for building Java applications, providing various tools and libraries for efficient development.
Spring Security: Provides authentication and authorization features for securing the application.
Thymeleaf: A templating engine for rendering HTML pages.
Bootstrap: A popular CSS framework for designing responsive and visually appealing web pages.
Project Structure
The project structure is organized as follows:

src/main/java: Contains the Java source code for the application.
com.example.gridauth: The main package for the application.
config: Configuration classes for Spring Boot.
controller: Controller classes for handling web requests.
model: Data model classes.
repository: Data access and database interaction classes.
service: Service classes to manage application logic.
src/main/resources: Contains configuration files and static resources.
templates: HTML templates for user interface.
application.properties: Application properties, including database configuration.
pom.xml: Maven project configuration file.
Getting Started
Clone this repository to your local machine:

Copy code
git clone [https://github.com/your-username/grid-authentication-system.git](https://github.com/Sweetsalt123/Pattern-Grid-Authetication/tree/master)
Import the project into your favorite IDE (e.g., IntelliJ IDEA, Eclipse).

Configure the database connection in application.properties.

Build and run the application.

Access the application in your web browser at http://localhost:8080.

Usage
User Registration:

Visit the registration page and provide a username and set a pattern for authentication.
User Authentication:

After registration, you can log in by drawing your pre-defined pattern on the grid.
Pattern Management:

Users can change their authentication pattern after logging in.
Security
The application employs security best practices, including secure storage of user credentials and the use of Spring Security for authentication and authorization.

Contributing
If you'd like to contribute to this project, please follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and test them.
Submit a pull request to the original repository.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
If you have any questions or need further assistance, please feel free to contact us at dhruvdhanorkar@gmail.com.

Thank you for your interest in the Pattern Grid Authentication System Project!
