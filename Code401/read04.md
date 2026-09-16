# Data Modeling 

## NoSQL VS. SQL 

The type of database that best fits a complex query-intensive enviroment is an **SQL Database** because SQL provides a powerful, standarized query language that creates a good relationship between data. 

When it comes to hierarchical data storage a **NoSQL database** is generally better because it can store information in structures as documents and key-value pairs like nested data. 

### Differences in scalability between SQL and NoSQL: 

In simple terms, imagine a SQL database like a computer that keeps updating. When you need additional power, you give that computer more storage or processing power.This would be considered *vertical scaling*. 
On the other hand, NoSQL is more like adding more computers or servers  when needed instead of increasing the power of a single computer. This would be considered *horizontal scaling*. 

# Modeling Techniques 

A **one-to-many relationship** means that one record in one table can be associated with multiple records in another table. We relate these tables by connecting a *primary key* from one table to a corresponding *foreign key* in another. 

* Prior to designing your relational databse, it might be useful to <u>create a diagram</u> of the database tables and their relationships. 

| Primary Key | Foreign Key | 
| ----------- | ----------- | 
| uniquely identifies each record in a table | a field that references the primary key of another table. creates the connection between 2 tables. 

## SQL VS. NoSQL

SQL keywords such as `SELECT`, `FROM`, `WHERE`, and `INSERT` are commands that are commonly written in uppercase to make the query easier to read. 

**Normalization** is the process of organizing data into related tables so that unnecessary duplication is reduced and the data remains consistent. Instead of repeatedly storing the same information in multiple places, you separate it into tables and connect those tables through relationships.

* **One-to-one:**  One employee has an employee card that belongs to them. 
* **One-to-many:** One department with mutiple emplyees that belong solely to that department. 
* **Many-to-many:** Many emplyees can work on many projects. One employee might work on several projects, while each project can have several employees.