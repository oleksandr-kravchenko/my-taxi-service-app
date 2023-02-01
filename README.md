# Simulator Taxi Service
#### This is a Simulator Taxi Service application that supports registration, authentication and CRUD operations, based on SOLID principles.
## Description
This is the simplest taxi emulator - designed to organize a taxi service and supports all the most necessary functions.

## Features
- registration as a driver;
- authentication as a driver;
- create/remove a car;
- create/remove a manufacturer;
- create/remove a driver;
- create connection a car with a driver;
- display a list of cars;
- display a list of manufacturers;
- display a list of drivers;
- display a list of cars by an authenticated driver.

## Technologies
- Java 11
- JDBC
- Servlet API
- JSP
- Maven
- MySQL
- JSTL
- HTML

## How to run
- Download and install the JDK (it uses Java 11).
- Download and install servlet container (Apache Tomcat) (it uses Tomcat 9.0.50).
- Download and install MySQL Server.
- Download and install MySQL Workbench.
- Create the schema and tables in MySql Workbench using data from file init_db.sql from package resources.
- Add your database URL, login, password and JDBC driver in taxi/util/ConnectionUtil. Example:
```bash
    private static final String URL =
          "jdbc:mysql://localhost:3306/taxi?useUnicode=true&serverTimezone=UTC";
    private static final String USERNAME = "root";
    private static final String PASSWORD = "1234";
    private static final String JDBC_DRIVER = "com.mysql.cj.jdbc.Driver";
```
- Run and enjoy the program