# Car Sharing

Project from [Java Backend Developer](https://hyperskill.org/tracks/12) track at
the [JetBrains Academy](https://hyperskill.org/)

## About

Simple implementation of the Car Sharing service

## Features

* **Manager menu**
    * Add car sharing companies
    * Add cars to the existing companies
* **Customer menu**
    * Renting cars
    * Returning cars
    * Getting rented car information
* **Add new customers**

## Realisation features
* **Menu interface** - [link](https://github.com/SmartOven/CarSharing/tree/main/src/main/java/carsharing/util/menu)
  * Working with the Menu interface object, that is being replaced by the different implementation of the interface
* **Storing data in database**
  * Database - H2
  * Working with database through DAO - Data Access Object Pattern - [link](https://github.com/SmartOven/CarSharing/tree/main/src/main/java/carsharing/db/dao)
  * Automated migrations to the current version - [link](https://github.com/SmartOven/CarSharing/blob/main/src/main/java/carsharing/db/MigrationManager.java)
* **Project properties**
  * Reading project properties from `application.properties` file - [link](https://github.com/SmartOven/CarSharing/blob/main/src/main/java/carsharing/util/AppProperties.java)
