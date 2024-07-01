# SkyLink Airline Database Project

## Table of Contents
1. [Introduction](#introduction)
2. [Key Functionalities](#key-functionalities)
3. [Problems in the Existing System](#problems-in-the-existing-system)
4. [Entity-Relationship Diagram (ERD)](#entity-relationship-diagram-erd)
5. [Top Down Approach](#top-down-approach)
6. [Bottom-Up Approach](#bottom-up-approach)
7. [Description of the Relations](#description-of-the-relations)
8. [CREATE TABLE Statements](#create-table-statements)
9. [Tables Data](#tables-data)
10. [Designing Views](#designing-views)
11. [Relational Data Model](#relational-data-model)
12. [SELECT Statements for Common Reports](#select-statements-for-common-reports)
13. [Functions, Stored Procedures, and Triggers](#functions-stored-procedures-and-triggers)

## Introduction
SkyLink Airline reservation system is designed to facilitate the booking, management, and monitoring of flights, passengers, tickets, and fares. It connects various entities involved in air travel, including passengers, flights, airlines, and airports, to streamline operations and improve efficiency.

## Key Functionalities
- **Booking and Ticket Management**: Booking flights, generating tickets, managing passenger details.
- **Passenger Management**: Storing passenger personal information, linking tickets to passenger records.
- **Flight Scheduling and Management**: Storing flight details, managing airport coordination.
- **Airline and Aircraft Management**: Maintaining airline details and tracking aircraft assignments.
- **Fare Management**: Managing class-based pricing and fare calculations.

## Problems in the Existing System
- **Manual Booking and Management**: Error-prone, time-consuming, data inconsistency.
- **Inefficient Data Handling**: Lack of real-time updates, poor customer experience.
- **Limited Reporting and Analytics**: Insufficient reporting, difficulty in tracking and analysis.
- **Security and Data Integrity Issues**: Vulnerability to data loss, weak data security.
- **Operational Inefficiencies**: Resource management challenges, coordination issues.

## Entity-Relationship Diagram (ERD)
The ERD outlines the relationships between various entities such as Passengers, Tickets, Flights, Airlines, and Airports.

## Top Down Approach
Identifying identities and defining unnormalized tables:
- **Passengers**
- **Ticket**
- **Ticket_Fare**
- **Airport**
- **Flight**
- **Air_Line**

Normalization process involves converting to 1NF, 2NF, and 3NF to ensure data integrity.

## Bottom-Up Approach
Starting with a comprehensive relation and breaking it down into sub-relations to eliminate redundancy and ensure normalization.

## Description of the Relations
Details of each table and their attributes, including primary keys and foreign keys to maintain referential integrity.

## CREATE TABLE Statements
SQL statements to create the necessary tables in the database.

## Tables Data
Sample data to populate the tables for testing and demonstration purposes.

## Designing Views
Creating views to simplify data retrieval and enhance user interaction with the database.

## Relational Data Model
Illustrating the associations among different relations in the database.

## SELECT Statements for Common Reports
SQL SELECT statements to generate common reports required by the system.

## Functions, Stored Procedures, and Triggers
Demonstrating the use of functions, stored procedures, and triggers to enhance database functionality.

---

### Faculty of Computer Science and Information Technology
- Punjab University College of Information and Technology
