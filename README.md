# **Biulding Data Models & Databases**

## What is a Data Model?

- A data model is an abstract model that organizes elements of data and standardizes how they relate to one another and to other properties of real-world entities.
 Think of an ecomerce web application for instance, we need a clearly defined data model connecting the relationships between entities such us customer details, 
products details, 

## Why is a Data model important?
1. Really important to organize data
2. organized data determines later data use case
3. Begin prior to biulding our applications, business logic and analytical models
4. iterative process

## Relational Model
- organizes data into one or more tables or columns and rows, with a unique key identifying each row

### Relational Databases
- its a digital database based on the relational model of data.. a sftware system used to maintain relational databases is a relational database management
system (RDBMS)

Types of RDBMS..
1. MySQL
2. PostgreSQL
3. Oracle
4. MSSQL

Database/Schema - a collection of Tables eg School Database or schema 

Tables/Relations - A group of rows sharing the same labeled elements eg Students, Subjects, Marks


### Advantages of a Relational Database
1. Ease of use - SQL
2. Ability to use joins
3. Ability to do aggregations and analytics
4. smaller Data Volumes
5. Flexibility of Queries
6. ACID transactions - data integrity

##ACID Properties of Databases
- A set of rules that define how a relational database should model data, 
can also be defined as a set of properties of a database transaction that guarantees data validity despite errors, power failures and other mishaps

A Database operation that satisfies the ACID properties is called a transaction, ACID properties are concerned with acgieving consistency and data integrity within a database, An example of this would 
be a person logging into their bank account. it is very important for them not to see any other persons details. The ACID properties consists of four major properties 

1. Atomicity - The guarantee that an entire database operation is handled as a single entity. This means that if a single query of a database operation fails, the entire operation fails
2. Consistency - ensures that all database operations will only permit valid transactions. This means that a database will guarantee that the database will be left in a stable and accurate state after the transaction
3. Isolation - Guarantees that all operations will be executed independently. This means that the database will look the same after a collection of operations were executed at the same time, or one after the other
4. Durability - Means that a database will be durable enough to remember all of its queued operations even durring a system failure (for example a restart or power outage)

### When to not use Relational Databases
1. Large amounts of Data
2. Need to be able to store different data types formats
3. Needs a flexible schema
4. Needs a high availability
5. Needs a horizontal scalability 
