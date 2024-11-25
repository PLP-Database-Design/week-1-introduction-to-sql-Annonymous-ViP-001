**NAME: CHARLES MUSYOKA CHARI**
## 1. State and Explain the components of a DBMS (Database Management System) 
A DBMS consists of the following components:
- **Hardware:** Physical devices for data storage and access.
- **Software:** The DBMS software that manages data (e.g., MySQL).
- **Data:** The collection of data stored in the database.
- **Users:** People interacting with the DBMS (e.g., administrators, developers).
## 2. What is a relational database? Give 4 examples.
A relational database is a kind of database that structures data in tables, or so often referred to as relations, each of which would contain rows, often reffered to as records, and columns, otherwise known as attributes.The tables are interconnected via relationships, many times using primary keys and foreign keys. it becomes easy to store, retrive, and manage data with this structure using SQL, refered to as Structured Query Language.
**Examples of Relational Databases:**
- **MySQL:**An open-source relational database management system that is widely used in web applications and other data-driven platforms.
- **PostgreSQL:** A powerful, open-source relational database well-known for extensibilty as well as adherence to standards.
- **Oracle Database:** Proprietary RDBMS used in enterprises for handling large-scale operations.
- **Microsoft SQL Server:** A relational database by Microsoft that finds widespread use in business and enterprise applications.
## 3. State and Explain three classifications of SQL?
**SQL:** Is classified based on the various types of operations perfomed using languages. Following are three main classifications:
- **Data Defination Language(DLL):** DDL commands are used to define, modify and delete the structure of database objects such as tables, schemas, indexes and views.
        ```Examples of DDL Commands:```
        **Create** - It creates a new table or database object.
        **ALTER** - Changes the structure of an existing object, like adding a column to a able.
        **DROP** - Removes a database object completely.
- **Data Manipulation Language(DML)Purpose:** DML commands are used to manage and manipulate the data in the database tables.
        ```Examples of DML Commands:```
        ***INSERT:*** Adds new records to a table.
        ***UPDATE:*** Changes records
        ***DELETE:*** Erases records from a table.
        ***SELECT:*** Retrieves data from the database(sometimes categorized as DQL, Data Query Language)
- **Data Control Language(DCL):** DCL Commands are used to control access to data and manage database permissions.
        ```Examples of DCL Commands:```
        ***GRANT:*** Grants specific privileges to a user or role
        ***REVOKE:*** Revokes previously granted privileges.
## 4. What is the difference between a Primary Key and a Foreign Key?
`A Primary Key` is a unique identifier for each record in a table, while `a foreign key` is a field in one table taht references the Primary Key in another table for relationships.
           [KEY DIFFERENCES]:
      ***Uniqueness:*** A Primary Key should have unique values for each row in a table.
                        A Foreign Key can have replicated valies because it represents relationships.
      ***Null Values:*** A Primary Key cannot contain NULL values
                         A Foreign Key can allow NULL VALUES if the relationship is optional.
      ***Purpose:*** A Primary Key uniquely identifies rows in its own    
      table. 
                     A Foreign Key enforces referential integrity by linking two tables
      ***Number Per Table:*** Each table can have only one Primary Key.
                              A table can have multiple Foreign Keys, each referencing a Primary Key in other tables.
                     ```EXAMPLE```
    - ``Primary Key``: *StudentID* uniquely identifies each student in the *Students* table.
    - ``Foreign Key``: *StudentID* in the *Enrollments* table references the *studentID* in the *Students* table to establish a relationship.                                 
## 5. What is an Entity-Relationship Diagram?
AN `ERD` is a structure and relationship visualization of a database. This diagram is utilized in the design of databases to model the logical structure of data and to show the relationship between different entities, or objects.
               **COMPONENTS OF AN ERD**
    - `Entities`- Represent objects or concepts. this icludes students, course. Shown as rectangles in the diagram.
    - `Attributes`- Represents properties or characteristics of an entity e.g Name, Age for a student. Depicted as ovals connected to their entities.
    - `Relationships`- Show how entities are related e.g Enrolls, Teaches.  Depicted as diamonds with lines connecting the entities.
    - `Primary keys and Foreign Keys:`Primary keys are underlined attributes that uniquely identify an entity. Foreign keys connect related entities and enforce referential integrity.           
## 6. What are the advantages of relational databases?
- Data Integrity and Accuracy
- Flexibility and Scalability
- Data Relationships
- Security Features
- Wide Adoption and support
## 7. State four types of data type used to store data in tables?
- Numeric Data Types
- Character or String Data Types
- Date and Time Data Types
- Binary Data Types
## 8. What is the purpose of a database management system (DBMS)?
- Data Storage and Organization
- Data Retrieval and Query Execution
- Data Integrity and Consistency
- Data Security
- Multi-User Access and Concurrency
- Backup and Recovery
- Data Relationship Management