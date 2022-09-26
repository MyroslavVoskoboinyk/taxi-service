# Taxi Service

This service is a simplified technical demo version of the taxi service.

## Features

- Registration like a new drivers
- Authentication and authorization like a driver
- Driver logout
- Create, update and remove a driver
- Create, update and remove a manufacture
- Create, update and remove a car
- Displaying info about drivers, cars and manufacturers

## Project Structure

The project based on N-Tier Architecture with the following tiers:

- DAO. Database interaction tier
- Service. Business logic implementation tier
- Controller. Web part interaction tier

## Technologies

- Java 11 
- Maven
- JDBC
- JSP
- MySQL
- Tomcat

## Launch Guide

1. Fork this repository.
2. Copy link of project.
3. Create new project from VCS.
4. Set necessary parameters in ConnectionUtil.class:
```
   private static final String URL = "URL";
   private static final String USERNAME = "USER NAME";
   private static final String PASSWORD = "PASSWORD";
   private static final String JDBC_DRIVER = "JDBC DRIVER";
```
5. Create necessary tables in your database using the file init_db.sql.
6. Install Tomcat v9.0.50.
7. Add and configure Tomcat Server in your IDEA.
8. Run the project.