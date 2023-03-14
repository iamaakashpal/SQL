
# What are Databases ?

✔️ A Database is a shared collection of logically related data and description of these data, designed to meet the information needs of an organization.

- **`Data Storage`**: A database is used to store large amounts of structured data, making it easily accessible, searchable, and retrievable.

- **`Data Analysis`**: A database can be used to perform complex data analysis, generate reports, and provide insights into the data.

- **`Record Keeping`**: A database is often used to keep track of important records, such as financial transactions, customer information, and inventory levels.

- **`Web Applications`**: Databases are an essential component of many web applications, providing dynamic content and user management.

# Properties of an Idea Database

- `Integrity` 
- `Availability` 
- `Security` 
- `Independent of Application` 
- `Concurrency`

# Types of Databases

- **`Relational Databases`** - Also known as SQL databases, these databases use a relational model to organize data into tables with rows and columns. 

- **`NoSQL Databases`** - These databases are designed to handle large amounts of unstructured or semi-structured data, such as documents, images, or videos. (MongoDB)

- **`Column Databases`** - These databases store data in columns rather than rows, making them well- suited for data warehousing and analytical applications. (Amazon Redshift, Google BigQuery)

- **`Graph Databases`** - These databases are used to store and query graph-structured data, such as social network connections or recommendation systems. (Neo4j, Amazon Neptune)

- **`Key-value databases`** - These databases store data as a collection of keys and values, making them well-suited for caching and simple data storage needs (Redis and Amazon DynamoDB)

# Relational Database

✔️ Also known as SQL databases, these databases use a relational model to organize data into tables with rows and columns.

![Relational Databases](https://raw.githubusercontent.com/iamaakashpal/SQL/main/images/Relational%20Databases.png)

# What is DBMS ?

✔️ A database management system (DBMS) is a software system that provides the interfaces and tools needed to store, organize, and manage data in a database. A DBMS acts as an intermediary between the database and the applications or users that access the data stored in the database.

# Functions of DBMS

- **`Data Management`** - Store, retrieve and modify 

- **`data Integrity`** - Maintain accuracy of 

- **`data Concurrency`** - Simultaneous data access for multiple users 

- **`Transaction`** - Modification to database must either be successful or must not happen at all 

- **`Security`** - Access to authorized users only

- **`Utilities`** - Data import/export, user management, backup, logging

# Database Keys

✔️ A key in a database is an attribute or a set of attributes that uniquely identifies a tuple (row) in a table. Keys play a crucial role in ensuring the integrity and reliability of a database by enforcing unique constraints on the data and establishing relationships between tables.

- **`Super Key`** - A Super key is a combination of columns that uniquely identifies any row within a relational database management system (RDBMS) table 

- **`Candidate key`** - A candidate key is a minimal Super key, meaning it has no redundant attributes. In other words, it's the smallest set of attributes that can be used to uniquely identify a tuple (row) in the table

- **`Primary Key`** - A primary key is a unique identifier for each tuple in a table. There can only be one primary key in a table, and it cannot contain null values.

- **`Alternate Key`** - An alternate key is a candidate key that is not used as the primary key. 

- **`Composite Key`** - A composite key is a primary key that is made up of two or more attributes. Composite keys are used when a single attribute is not sufficient to uniquely identify a tuple in a table.

- **`Surrogate Key`** -

- **`Foreign Key`** - A foreign key is a primary key from one table that is used to establish a relationship with another table.

# Cardinality of Relationship

✔️ Cardinality in database relationships refers to the number of occurrences of an entity in a relationship with another entity. Cardinality defines the number of instances of one entity that can be associated with a single instance of the related entity.

# Drawbacks of Database

- **`Complexity:`** Setting up and maintaining a database can be complex and time- consuming, especially for large and complex systems.

- **`Cost:`** The cost of setting up and maintaining a database, including hardware, software, and personnel, can be high.

- **`Scalability:`** As the amount of data stored in a database grows, it can become more difficult to manage, leading to performance and scalability issues.

- **`Data Integrity:`** Ensuring the accuracy and consistency of data stored in a database can be a challenge, especially when multiple users are updating the data simultaneously.

- **`Security:`** Securing a database from unauthorized access and protecting sensitive information can be difficult, especially with the increasing threat of cyber attacks. 

- **`Data Migration:`** Moving data from one database to another or upgrading to a new database can be a complex and time-consuming process.

- **`Flexibility:`** The structure of a database is often rigid and inflexible, making it difficult to adapt to changing requirements or to accommodate new types of data.
