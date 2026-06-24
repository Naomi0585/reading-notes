<table>
<tr>
<th>Feature(s)</th>
<th>SQL</TH>
<th>NoSQL</th>
</tr>
<tr>
<td>Data Structure</td>
<td> Structured data with tables</td>
<td>Unstructured or semi-structured data</td>
</tr>
<tr>
<td>Schema</td>
<td>Fixed schema</td>
<td>Dynamic/Flexible schema</td>
</tr>
<tr>
<td>Scalability</td>
<td>Vertical scaling</td>
<td>Horizontal scaling</td>
</tr>
<tr>
<td>Relationships</td>
<td>Strong support for pairings</td>
<td>Limited pairing; data is often stored together</td>
</tr>
<tr>
<td>Examples</td>
<td>MySQL. PostgreSQL, Oracle</td>
<td>MongoDB, Cassandra, Redis</td>
</tr>
<table>


# SQL & NoSQL 

**SQL** databases are primarily called as *Relational Databases*; whereas **NoSQL** database are primarily called as *non-relational* or *distributed database*. **SQL** databases are best for structured data with a predefined schema, where relationships between data are important. A good example for these type of databases are banking systems that store structured data such as customer accounts, balances and transanction history. For **NoSQL** unstructured databases are best because they may change frequently and does not require a fixed schema. Social media platforms are a good example for these type of databases because in this case different types of data are stored such as comments, images and videos. Also, **NoSQL** databases are generally better for *hierarchical* data storage because they can store nested and flexible data structures. **NoSQL** databases are also best for scalability because they are designed to scale horizontally across multiple servers. 

## SQL VS. NoSQL 

* **SQL** stands for *Structured Query Language*. Within *SQL* we can find *relational databases* which store data in tables made up of rows and columns, with relationships between the tables. Relational databases work with a structured schema, meaning that the format of the data is defined before the data is added usually with columns or tables. Since we've introduced a new term it's only proper to mention what it means, a **schema** is a blueprint of a database that defines tables, columns, data types and relationships between tables. 

* A **NoSQL** database is a *non-relational database* designed to store data in flexible formats, such as documents, key value pairs, graphs or columns. Instead of storing data in tables with fixed columns, **NoSQL** databases store data in flexible structures.For example, document databases store data as JSON-like documents, allowing different records to have different fields.A disadvantage of NoSQL databases is that they may provide less support for complex joins and relationships than SQL databases, and maintaining data consistency across large systems can be more challenging

* A **MongoDB** database contains collections, and each collection  MongoDB is more flexible because it does not require a fixed schema. Documents in the same collection can have different fields and structures.
