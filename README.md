# Game Store Inventory Management

## Overview

This is a group final project for managing the inventory of a video game store. The application is a full-stack web service developed using agile techniques in a group setting of 3-4 learners. The main goal is to design, document, and implement a simple back-end API for inventory management via REST and GraphQL.

## Features

-   Manage the inventory of video games, game consoles, and T-shirts.
-   Perform standard CRUD operations for games, consoles, and T-shirts.
-   Search for games by studio, ESRB rating, and title.
-   Search for consoles by manufacturer.
-   Search for T-shirts by color and size.
-   Create an invoice by supplying the customer and item details.
-   Support for GraphQL queries to retrieve games and consoles information.

## Technologies Used

-   Java 11
-   Spring Boot
-   Spring MVC
-   JPA (Java Persistence API)
-   JUnit
-   MockMVC
-   JSR303 (for input validation)
-   GraphQL

## Setup and Installation

1.  Clone the repository.

bashCopy code

`git clone https://github.com/yourusername/gamestore-inventory-management.git` 

2.  Open the project in IntelliJ.
3.  Configure your database settings in `application.properties`.
4.  Run the application.
5.  The application will be accessible at `http://localhost:8080`.



## API Endpoints

### REST API

-   `GET /games`: Retrieves a list of all games.
-   `GET /games/{id}`: Retrieves a game by its ID.
-   `POST /games`: Creates a new game.
-   `PUT /games/{id}`: Updates an existing game by its ID.
-   `DELETE /games/{id}`: Deletes a game by its ID.
-   ...

### GraphQL API

-   `GET /graphql/games`: Retrieves a list of all games.
-   `GET /graphql/games/{id}`: Retrieves a game by its ID.
-   ...

## Testing

-   All REST API routes are tested using MockMVC.
-   The service layer methods are tested using JUnit and mock objects where appropriate.
-   Integration tests are written for all repositories to test basic CRUD operations and any custom methods.
