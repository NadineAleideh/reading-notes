# Introduction to Databases and ERDs

## Why this topic matters

Data bases are very important beacuse they are the foundation for storing and managing data in applications. They provide a structured and reliable way to store and retrieve data, enabling applications to function properly and deliver value to users. So, understanding databases and ERDs helps in creating well-structured, organized, and reliable systems for storing and managing data.

### Do some research on what a Database Schema is

  1. What is a Schema?

     Schema is the overall description of the database, it's the basic structure of how the  data will be stored, also explains the constraints and relationships.

  2. Why do we use them?

     - Schemas provide a way to define and organize the data stored in a database.
     - Ensure data integrity, consistency, and facilitate efficient data management and querying.
     - help in separating different aspects of a database, such as tables, views, and procedures, making it easier to maintain and understand the database structure.

  3. What do they look like?

     Schema shows the creation of tables (entities), specifying columns, data types, constraints  and relationships between tables.

### What are the different types of Database Keys?

  1. What is a Primary Key?

     It is the first key used to identify one and only one instance of an entity uniquely.

  2. What is a Foreign Key?

     Foreign key is the column of the table used to point to the primary key of another table.

  3. What is a Composite Key?

     A combination of columns that make up a unique identifier for a table.

  4. How are they different? When do you use 1 over the others?

     The primary key is used to uniquely identify each record in a table. It is essential and commonly used in every table to ensure data integrity and efficient data retrieval.

     Foreign keys establish relationships between tables by referencing the primary key of another table. They are used when establishing relationships between tables, such as one-to-many or many-to-many relationships.

     Composite keys are used when a single column cannot guarantee uniqueness, but the combination of multiple columns can uniquely identify records. They are used in situations where a composite key is necessary to maintain data integrity and uniqueness.

### What are Relationships in a relational database?

  1. What is a 1:1 relationship?

       A one-to-one relationship in a relational database represents a relationship between two entities where each record in one entity corresponds to exactly one record in the other entity.

  2. What is a Many:Many relationship?

     It is between two entities where multiple records in one entity can be associated with multiple records in the other entity. This relationship is implemented using an intermediary table, often called a junction table or associative table, that stores the associations between the two entities.

  3. How about a 1: Many or a Many:1?

      It reperesents that a single record in one entity can be associated with multiple records in another entity, but each record in the other entity can be associated with only one record in the first entity. It is the most common relationship type in a relational database.

### Things I want to know more about

 Practice more How to Converet a real requierments to a complete data base.
