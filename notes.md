## What is Data?

- A piece of information that can be translated into a form for efficient movement and processing is called data.
- Data is interchangeable infromation between two computer system.

## What is Database?

- A database is a collection of data that is organized in a structured way it is stored and accessed by computer system.
- Database are managed by (Database Management System)DBMS, a software which is use to manage data by using some programming language.

## What is the difference between sql and nosql database?

|                     | sql                                                                                    | nosql                                                                                                                                                                                                |
| ------------------- | -------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Dabase Model        | It is a Relational database(RDB)[structured schema]                                    | It is a document-oriented database[schema-uss/flexible schema]                                                                                                                                       |
| Data Representation | It stores the data in the form of tables                                               | It stores the data in JSON like documents                                                                                                                                                            |
| Data Access         | It uses SQL for accessing data                                                         | It provides JSON query language support                                                                                                                                                              |
| Example             | <img src="https://d2jdgazzki9vjm.cloudfront.net/mysql/images/mysql-create-table3.png"> | <img src="https://www.researchgate.net/publication/338144434/figure/fig3/AS:839633541795841@1577195644618/Example-of-data-stored-in-noSQL-database-a-Five-key-values-pairs-b-2D-coordinates-of.png"> |
|                     | Data store in tables with columns and rows.                                            | Data stored in collection with fields and collection.(key-value pairs)                                                                                                                               |
|                     | Eg:- MySQL, PostgreSQL, ORACLE, SQL Server, Microsoft SQL server.                      | Eg:- MongoDB, Cassandra, Cauchbase, Amazon DynamoDB, Radis.                                                                                                                                          |
| Joins               | SQL Server uses joins to access data from joined tables.                               | It does not support joins because it is a non-relational database.                                                                                                                                   |

# MongoDB

- MongoDB is an open-source, cross-platform, document-oriented database program that is designed to store a large scale of data and allows us to work with that data efficiently.
- It is a `Nosql` database which means the data in mongodb are not stored in the form of table.
- MongoDB uses a document storage format called `BSON`(Binary JSON), which is a binary format of JSON document.
