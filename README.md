# Web_In_home_activity_Spring_Framework_01
In-Home Activity
Web In-home activity - Spring Framework
Preface
Before you start coding, read this document from top to bottom. It contains some valuable information that will make your work easier. In this activity, you will get to know Spring Initializr, Gradle build tool, and Rest Controllers

Description
You are given a project with the name BeerTag. Before each session, you will have to submit an in-home activity with which to practice the theory for the corresponding session. You can use this document and the videos to guide you through the steps.

Architecture
This is the session in which you will start the project from scratch.

Models
Note: All validation intervals are inclusive (closed).
Note: Put your classes in a models package.
Beer
For now, each beer in the system will have an id, name, abv.
id should be positive.
Exception message: Id should be positive.
name should not be null and between 2 and 20 symbols long.
Exception message: Name can't be empty.
Exception message: Name should be between 2 and 20 symbols.
abv should be positive.
Exception message: ABV should be positive.
Controllers
Note: Put your classes in a controllers package.
Note: Use ResponseStatusException
BeerRestController
For now, our REST controller will have a list of beers and the following endpoints:
get - returns the list of beers.
get - returns a beer by id, if found.
Exception message: Beer with id {id} not found.
create - adds beer to the list.
update - returns the updated beer, if found.
Exception message: Beer with id {id} not found.
delete - does not return anything.
Exception message: Beer with id {id} not found.
Step by step guide
Create a Spring project
Use Spring Initializr
Use Gradle Groovy as a build tool.
Use Java 17 and Spring Boot 3.1
Choose the Spring Web as a dependency.
Create the Beer model & Beer Rest Controller
Make server error message appear.`
Validate the fields.
Follow the REST principles when you create the endpoints.
Test the endpoint with Postman
