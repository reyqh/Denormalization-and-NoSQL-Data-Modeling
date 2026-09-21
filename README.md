# Denormalization-and-NoSQL-Data-Modeling
Database project exploring denormalization and NoSQL data modelling using a Bike Store database. Includes analysis of denormalisation opportunities, aggregate boundary design, UML modelling, and JSON document creation.

# Denormalization and NoSQL Modelling

This project explores database denormalization and NoSQL data modelling using a Bike Store database.

## Project Overview

The project is divided into two main parts:

### 1. Denormalization
The first part identifies opportunities to denormalize a normalized relational database. The aim was to reduce the number of joins required for frequently accessed information and improve read performance. Examples include combining user and ZIP-code information, embedding contact details within advertiser clients, and storing user interest information directly with users. :contentReference[oaicite:0]{index=0}

### 2. NoSQL Modelling
The second part focuses on modelling a Bike Store database using NoSQL concepts. An **Order** was selected as the aggregate root, containing related customer, store, staff, order item, and product information. A UML aggregate model was created to represent this structure. :contentReference[oaicite:1]{index=1}

The final stage involved representing the aggregate as JSON documents, with each order stored as a complete object containing its related data. 

## Key Concepts

- Database normalization and denormalization
- NoSQL data modelling
- Aggregate boundaries
- Aggregate roots
- UML modelling
- JSON document structures
- Embedded/nested data
- Reducing database joins
- Read-performance considerations
