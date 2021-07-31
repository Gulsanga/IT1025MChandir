# Executive Summary
Talk about what the goal of this lab is !
we learned about the role that data and databases play in the context of information systems. Data is made up of small facts and information without context. If you give data context, then you have information. Knowledge is gained when information is consumed and used for decision making. A database is an organized collection of related information
# Data, Information and Knowledge 
## Relational Data

* What is the difference between data, information and knowledge? 
Data are sets of signs that represent empirical stimuli or perceptions,
information is a set of signs, which represent empirical knowledge, and
knowledge is a set of signs that represent the meaning (or the content) of thoughts that the individual justifiably believes that they are true
* If you were creating a database for a small company and two tables you identify are customers and orders explain the following:
(be sure to use the example in the chapter as a guide - customers and orders would be like clubs and events) 
a) What would be the primary key in the customers and orders table? 
Notice that the customer number column is the primary key of the customers table and that the same column is a foreign key in the orders table. The customer number column in orders therefore serves to relate orders to the customers to which they belong.
b) How would the customers and orders table be related? 
Customers and Orders tables are related via the CustomerId fields in both tables (it is the primary key in Customers, and foreign key in Orders table). When you model that as an Entity relation than you have the above diagram. Customer entity have an "Orders" navigation property (via customerId) that points to a particular Customer's Orders.
c) What would be the foreign key in the orders table? 
 The FOREIGN KEY constraint is a key used to link two tables together. A FOREIGN KEY is a field (or collection of fields) in one table that refers to the PRIMARY KEY in another table. The following SQL creates a FOREIGN KEY on the "PersonID" column when the "Orders" table is created:
d) The orders table would likely have a date fiel  Explain why it is important to properly define the data type of a field. 
 
## Big Data

* Briefly describe the four "Vs" of big data.  Volume.
Variety.Each piece of data, or core information, will require specific treatment. In addition, each type of data will require specific storage needs (the storage of an e-mail will be much less than that of a video).
Velocity.It is very possible that Variety and Veracity would not be so relevant and would not be so much pressure when facing a Big Data initiative if it were not for the high Volume of information that has to be handled and, above all, for the velocity at which the information has to be generated and managed.
Veracity.This V will refer to both data quality and availability. When it comes to traditional business analytics, the source of the data is going to be much smaller in both quantity and variety. However, the organization will have more control over them, and their veracity will be greater.
Value. You may have heard on more than one occasion that Big Data is nothing more than business intelligence, but in a very large format. More data, however, does not necessarily mean it is Big Data.
* What types of technology have driven the increased need for big data? 
 some key technologies that enable Big Data for Businesses: One of the prime tools for businesses to avoid risks in decision making, predictive analytics can help businesses. Predictive analytics hardware and software solutions can be utilised for discovery, evaluation and deployment of predictive scenarios by processing big data.
# Structured Query Language (SQL)
* Explain RDBMS and how it relates to SQL and the purpose of SQL .. It enables a user to create, read, update and delete relational databases and tables. All the RDBMS like MySQL, Informix, Oracle, MS Access and SQL Server use SQL as their standard database language. SQL allows users to query the database in a number of ways, using English-like statements. Structure query language is not case sensitive.
* Pick two related tables from the diagram provided in the "module - SQL" and explain the relationship between them
a) which is the primary key?n the relational model of databases, a primary key is a specific choice of a minimal set of attributes that uniquely specify a tuple in a relation. Informally, a primary key is "which attributes identify a record", and in simple cases are simply a single attribute: a unique id. 
b) which is the foreign key?A foreign key is a set of attributes in a table that refers to the primary key of another table. The foreign key links these two tables. Another way to put it: In the context of relational databases, a foreign key is a set of attributes subject to a certain kind of inclusion dependency constraints, specifically a constraint that the tuples consisting of the foreign key attributes in one relation, R, must also exist in some other (not necessarily distinct) relation, S, and furthermore that those attributes must also be a candidate key in S
* Using W3Schools, try out a 
a) select statement 
a) where clause 
and upload screenshots of the results.
* Explain how SQL injections are a security threat and what can be done to reduce the issue. 
  SQL injection (SQLi) is a technique used to inject malicious code into existing SQL statements. These injections make it possible for malicious users to bypass existing security controls and gain unauthorized access to obtain, modify, and extract data, including customer records, intellectual property, or personal information.
# Conclusion
Include what you have learnt from this lab
 Relational databases are the most widely used type of database, where data is structured into tables and all tables must be related to each other through unique identifiers. A database management system (DBMS) is a software application that is used to create and manage databases, and can take the form of a personal DBMS, used by one person, or an enterprise DBMS that can be used by multiple users. 
