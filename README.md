# Overview
The Restaurant Management Application is a Spring Boot-based web application designed to help manage restaurant information. It allows users to perform various operations related to restaurant management, including adding new restaurants, updating specialties, and deleting restaurants from the system.

# Technologies
<li> Framework : Spring Boot </li>
<li> Language: Java </li>
<li> Build Tool : Maven </li>

# Data Flow
## Controller
The Controller layer is responsible for handling incoming HTTP requests and delegating them to the appropriate services

## Services 
The Services layer implements the core business logic, data processing, and interaction with the data repository. Key responsibilities include:

Validating input data.
Performing CRUD operations on restaurant data.
Handling data transformations and interactions with external systems (if applicable

## Repository
The Repository layer manages data access to the underlying database. It handles database operations such as Create, Read, Update, and Delete (CRUD) for restaurant data. Additionally, it may include data mapping and conversion between Java objects and database entities.

## Restaurant 
The "Restaurant" table stores restaurant-related information, including restaurant IDs, names, addresses, contact information, specialties, staff counts, types, and timestamps for record creation and modification.

This database design ensures data integrity and provides a structured approach to managing restaurant information within the application.

## Restaurant Class

The Restaurant class defines the structure for restaurant data and includes the following fields:

restaurantId (Restaurant ID): An integer that serves as a unique identifier for each restaurant.
restaurantName (Restaurant Name): A string representing the restaurant's name.
restaurantAddress (Restaurant Address): A string containing the restaurant's address.
restaurantContact (Restaurant Contact): A string representing the restaurant's contact number (e.g., 911234567890).
restaurantEmail (Restaurant Email): A string containing the restaurant's email address.
restaurantSpecialty (Restaurant Specialty): A string representing the restaurant's specialty.
numberOfStaff (Number of Staff): An integer indicating the number of staff members.
restaurantType (Restaurant Type): An enumeration specifying the restaurant type (e.g., FAMILY, CAFE, FAST_FOOD)

## Type Enum
The Type enum enumerates the possible restaurant types:

FAMILY: Represents a family restaurant.
CAFE: Represents a cafe.
FAST_FOOD: Represents a fast-food restaurant.

## ArrayList
utilizes the ArrayList data structure to store and manage lists of Restaurant objects in various parts of the application. ArrayList provides dynamic sizing and efficient element retrieval, making it suitable for storing restaurant records and performing operations on them.

## Project Summary 
utilizes the ArrayList data structure to store and manage lists of Restaurant objects in various parts of the application. ArrayList provides dynamic sizing and efficient element retrieval, making it suitable for storing restaurant records and performing operations on them.
