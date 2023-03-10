# 🎥 my-cinema-app 🕶️

## List of content
- [Description](#description)
- [Possibilities](#possibilities)
- [Stack of technologies](#stack-of-technologies)
- [Installing](#installing)
- [Getting started](#getting-started)
- [Authors](#authors)

## Description
Hi to all! This is my implementation of the cinema, the purpose of this project was to test the capabilities of Hibernate and Spring in interaction with the MySQL database, as well as to acquire practical skills in working with GitHub and publishing the project in public access. <hr>

## Possibilities
- There are two types of access to the functionality, Administrator and User
- Creating your own user, or use two accounts by default
- Configuration of the main objects present in the cinema (tickets, films, cinema halls, screenings, etc.
- Retrieving any generated data from the DB

## Stack of technologies
- Java 11
- Hibernate framework
- Spring framework
- REST
- SQL
- MySQL
- Maven
- Tomcat

## Installing
1. Download project from this repository and add to IDE as Maven project;
2. Add project to your IDE as Maven project;
3. Install and configure Tomcat;
4. Install and configure MySQL + MySQL Workbench;

## Getting started
1. In the db.properties file, change the data to what is relevant for your DB;
2. Make sure all dependencies from pom.xml are loaded;
3. Add new run configuration in IDEA: Run -> Edit configurations... -> Add new run configuration... -> Tomcat Server -> Local -> Fix -> Select "my-cinema-app:war exploded" (In graph "Application context" must be the only "/");
4. Create the cinema schema for the project in DB;
5. Run the project;
6. Use Postman to send requests, a list of all requests is available in the SecurityConfig class.

## Authors
[Ivan Kharchenko](https://github.com/Pro1OOGamer)