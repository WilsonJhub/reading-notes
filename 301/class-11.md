# Mongo and Mongoose  

## NoSQL vs SQL  
 Differences  
  - SQL databases are primarily called as Relational Database  
      - NoSQL database are primarily called as non-relational or distributed database.
  - SQL databases defines and manipulates data based structured query language   
    - A NoSQL database has dynamic schema for unstructured data.  
  - SQL databases are table-based on the other hand NoSQL databases are either key-value pairs, document-based, graph databases or wide-column stores.  
  - SQL databases follow ACID properties (Atomicity, Consistency, Isolation and Durability) whereas the NoSQL database follows the Brewers CAP theorem (Consistency, Availability and Partition tolerance).  

  1. What kind of data is a good fit for an SQL database?  
    -  When you have data that needs to have a strict schema. ie - users, products, orders. 
  2. Give a real world example.  
    - users, products, orders.
  3. What kind of data is a good fit a NoSQLdatabas?  
    - When you have a lot of reads and not a lot of writes.  
  4. Give a real world example.  
    - When reading the price or viewing a product. Those datas don't have to change very often.  
  5. Which type of database is best for hierarchical data storage?  
    - SQL
  6. Which type of database is best for scalability?  
    - NoSQL


  1. What does SQL stand for?
    - Structured Query Language
  2. What is a relational database?  
    - A relational database is a type of database that stores and provides access to data points that are related to one another.
  3. What type of structure does relational database work with?
    - collection of data items with pre-defined relationships between them. Organized as a set of tables with columns and rows. 
  4. What is a *schema*?
    - A schema is a list of logical structures of data.
  5. What is a NoSQL database?  
    - Non-tabular databases and store data differently than relational tables.
  6. How does it work?  
    - Types of NoSQL databases include pure document databases, key-value stores, wide-column databases, and graph databases.
  7. What is inside of a Mongo database?  
    - MongoDB stores data records as documents (specifically BSON documents) which are gathered together in collections.
  8. Which is more flexible - SQL or MongoDB? and why.
    - NoSQL is more flexible. 
  9. What is the disadvantage of a NoSQL database?
    - Compatibility issues with SQL instructions. New databases use their own characteristics in the query language and they're not yet 100% compatible with the SQL used in relational databases.