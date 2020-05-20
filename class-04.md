# Read 03 ~ Data Modeling & NoSQL Databases
> By Abdallah obaid

**NAME**     | **URL**
------------ | -------------
Home         | [Home](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/).
 Prep        | [Prep: Engineering Topics](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/Prep).
 Read 01     | [Node Ecosystem, TDD, CI/CD](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-01).
 Read 02     | [Classes, Inheritance, Functional](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-02).
 Read 03     | [Data Modeling & NoSQL Databases](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-03).
 Read 04     | [Advanced Mongo/Mongoose](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-04).
 Read 05     | [Linked Lists](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-05).
 Read 06     | [HTTP and REST](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-06).
 Read 07     | [Express](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-07).
 Read 08     | [Express Routing & Connected API](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-08).
 Read 09     | [API Server](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-09).
 Read 10     | [Stacks and Queues](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-10).
 Read 11     | [Authentication](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-11).
 Read 12     | [OAuth](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-12).
 Read 13     | [Bearer Authorization](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-13).
 Read 14     | [Access Control (ACL)](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-14).
 Read 15     | [Trees](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-15).
 Read 16     | [Event Driven Applications](https://abdallah-401-advanced-javascript.github.io/reading-notes-401/class-16).

 
----------------------------------
# Data Modeling & NoSQL Databases:-
----------------------------------

 ## why would a developer choose to make data models?
  1. Ensures that all data objects required by the database are accurately represented.
  2. Provides a clear picture of the base data and can be used by database developers to.
  3. It is also helpful to identify missing and redundant data.

 ## What purpose do CRUD operations serve?
   * Create, read, update, delete each one can be alocated with one of the "REST" methodes and its the Four basic functions of persistent storage in the database.

 ## What kind of database is Postgres? What kind of database is MongoDB?
   *postgres is a tabular relational database (sql) and mongoDb is not atabular relational database (no-sql)
   
 ## What is Mongoose and why do we need it?
   * Is an Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB
 ## Define three related pieces of data in a possible application. An example for a store application might be  Product, Category and Department. Describe the constraints and rules on each piece of data and how you would relate these pieces to each other. For example, each Product has a Category and belongs in a Department.
   1. Speed.
   2. Distance. 
   3. Time.
   * Speed = Sistance / Time

 ## Describe how NoSQL Databases scale horizontally:
   * NoSQL databases are designed to expand horizontally and in Horizontal scaling means that you scale by adding more machines into your pool of resources.

 ## Give one strong argument for and against NoSQL Databases:
   * postgres is a tabular relational database (sql) and mongoDb is not atabular relational database (no-sql)

 ## Name 3 cloud based NoSQL Databases:
   * Oracle, mongodb, CouchDB.


 ## Database:
   * A database is an organized collection of data, generally stored and accessed electronically from a computer system. Where databases are more complex they are often developed using formal design and modeling techniques.

 ## Data model:
   * Its an abstract model that we use to organize the data elements and it give us the role of relations between them.

 ## CRUD:
   * Its refer to create, read, update, delete each one can be alocated with one of the "REST" methodes and its the Four basic functions of persistent storage in the database.

 ## schema:


 ## Database schema:
   * Logecal structure for the database.
   * Describes the organization of data.
   * Represents the relationship between various tables in a database.
 

 ## Sanitize:
   * The process of deliberately, permanently and irreversibly removing or destroying the data stored on a memory device to make it unrecoverable

 ## Structured Query Language (SQL):
   * SQL is a standard language for accessing and manipulating databases.

 ## Non SQL (NoSQL):
   * Provides a mechanism for storage and retrieval of data that is modeled in means **other than the tabular relations** used in relational databases.

 ## MongoDB:
   * Is a cross-platform document-oriented database program. Classified as a **NoSQL database program**, MongoDB uses **JSON-like** documents with schema

 ## mongoose:
   * Is an Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB

 ## Record:
   * Alot of fields that contains data about one same thing.

 ## Document:
   * Nonrelational database that is designed to store and query data as JSON-like documents.

 ## Object-relational mapping:
   * A programming technique for converting data between incompatible type systems using object-oriented programming languages.   


 
 ![npm](./Img/database.gif)