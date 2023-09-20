# Class 04 Summary
## Code 401 - Advanced Software Development in Full-Stack JavaScript

> These topics relates because, when creating CRUD applications, nosql or sql databases are usually involved.

### Reading - nosql vs sql
1. What type of database is the best fit for the complex query intensive environment?
> In a complex query intensive environment, a relational SQL database like PostgreSQL or MySQL is often the best fit due to its strong support for structured data and advanced querying capabilities.
2. What type of database is the best fit for hierarchical data storage?
> For hierarchical data storage, a NoSQL database like MongoDB is well-suited, as they can handle nested and unstructured data more effectively.
3. Describe the differences in scalability between a SQl and NoSQL database as though you were speaking to a non-technical friend.
> Imagine SQL is like a well-organized library where books are neatly arranged in shelves but can be slow to expand, while NoSQL is like a flexible stack of papers that can quickly grow and adapt to different needs without much fuss.

### sql modeling techniques
1. Among data tables, what is a one-to-many relationship and how do we “relate” them?
> In data tables, a one-to-many relationship means that one record in one table can be associated with multiple records in another table. We "relate" them by using a foreign key in the "many" side table that references the primary key in the "one" side table.
2. Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
> **sketch** a **diagram**
3. Explain the difference between a primary and foreign key.
> A primary key is a unique identifier for each record in a table, ensuring each row has a distinct identity. A foreign key, on the other hand, is a field in a table that links to the primary key in another table, creating a connection between the two tables to establish relationships.

### Videos - nosql vs sql
1. How do we treat keywords and parameters differently in SQL syntax?
> In SQL syntax, keywords as reserved words that have special meanings and cannot be used as names for tables or columns. On teh other hand, parameters are placeholders for values that can be dynamically inserted into SQL queries to make them more flexible and reusable.
2. Define normalization within the context of schemas and data.
> Normalization is the process of organizing and structuring data in a relational database to minimize redundancy and dependency, which helps improve data integrity and efficiency.
3. Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
> A one-to-one relationship as a key and a lock, where each key (person) matches only one lock. A one-to-many relationship is like a library where one librarian (parent) manages multiple books (children), but each book has only one librarian. A many-to-many relationship is like social media friendships where people can have multiple friends and each friend can be friends with multiple others.

### Reflection
1. What are your learning goals after reading and reviewing the class README?

### Things I want to learn more about.
> I want to learn more about utilizing sql database because we already used a nosql database - MongoDB on Code 301.

#### I utilized ChatGPT for some of the questions.
