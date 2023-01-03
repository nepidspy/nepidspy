- 👋 Hi, I’m @nepidspy
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
nepidspy/nepidspy is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Data engineering meta
In software engineering, what are the difference between an edge case, a corner case, a base case and a boundary case? Particularly think we've database development, it's easy to over-complicate solutions, especially when you're doing data modeling and data storage, you want to cover every possible variation of data, every different use case, edge case for using that data. Start small, iterate frequently, write more often.
Store the data, form connections or relationships between segmented areas of the data, filter the data to show relevant records, search data to return matching records, and have functions to allow the data to be updated, changed, and deleted as required.
Database=data organize systematically.
Entity(relational elements) is like table where data is separated and stored. It contains rows and columns that stop data relating to specific element. 
As you just learned, an entity is like a table. It contains rows and columns that store data relating to a specific element. In other words, these are relational elements. They're related to one another. 
These entities could be physical representations like an employee, a customer, or a product. Or they could be conceptual like an order, an invoice or a quotation. Entities then store data in a table-like format against the attributes or features related to the element. In the relational database world, these entities are known as relations or tables. The attributes become the columns of the table. Each table row represents an instance of that entity.
￼
An object-oriented database is where data is stored in the form of objects instead of tables or relations. An example of this kind of database could be an online bookstore. 
Column fields rows records. All these fields and rows work together to store information on the customer, also known as the entity. Every row and record in the customer table is an instance of the customer entity.

area chart = line chart + bar chart include: dual axis charts,  
Big data complex highly un or semi structured data that can increase in volume with time. Data that can grow exponentially with time. 
unstructured data = no sequel databases=database store data in a variety of different formats and flexible structure for scale and store.
No sequel databases are used by social media platforms, the Internet of Things, artificial intelligence and other applications that generate massive amounts of unstructured data types of no sequel databases include document databases. Key value databases and graph databases.

Traditional database systems could deal with structured data using tables, records and relationships. But big data is a whole new challenge. Big data is a combination of structured, semi structured and unstructured data collected from many different sources and it adds more power to data because it can address complex business problems that traditionally structured data can't handle. 
￼
cloud databases=free from maintenance and storage costs=more affordable solution.
Another trend and databases is business intelligence or B. I. 
￼
New trends are constantly emerging in database technology and they'll keep advancing with time.
The chronological order of the development of databases is as follows: 
* (1970s-1990s) - Flat files, hierarchical and network  
* (1980s-present) - Relational  
* (1990s- present) - Object-oriented, object-relational, web-enabled 
Unlike relational databases, object-oriented databases work in the framework of real programming languages like Java and C++, for example. Instead of tables, there are entities or classes like Author, Book and Customer with their attributes and behaviors. 

It’s possible to represent data according to OO concepts like inheritance and parent-child relationships among data. For example, an Author and Customer are both descendants of Person. Thus, a person is a generic entity that can represent both an Author and a Customer.
These are some of the advantages of NoSQL databases:
* Higher scalability
* Distributed
* Lower costs
* A flexible schema
* Can process unstructured and semi-structured data 
* Has no complex relationships 
Over time there were different types of NoSQL databases that were introduced:
* Document databases store data in documents similar to JSON (JavaScript Object Notation) objects. Each document contains pairs of fields and values. The values can typically be a variety of types including things like strings, numbers, booleans, arrays, or objects. 
* Key-value databases are a simpler type of database where each item contains keys and values. 
* Wide-column databases store data in tables, rows, and dynamic columns. 
* Graph databases store data in nodes and edges. Nodes typically store information about people, places, and things, while edges store information about the relationships between the nodes. 

SQL is the standard language that can be used with all databases. It's particularly useful when working with relational databases, which require a language that can interact with structured data. Some examples of relational databases that SQL can interact with include MySQL, PostgreSQL, Oracle, and Microsoft SQL Server. 

The next question this raises, is how does a database interpret or read and execute instructions given using SQL. A database interprets and make sense of SQL instructions with the use of a Database Management System or DBMS.
￼
As a web developer, you'll execute all SQL instructions on a database using a DBMS. The DBMS takes responsibility for transforming SQL instructions into a form that's understood by the underlying database. 

demonstrate an understanding of the SQL subsets and sub languages:
CRUD in operational terms, create, add or insert data, read data, update existing data and delete data alongside CRUD operations, there are many other things that SQL can do depending on what SQL is used for. It can be divided into many subsections or sub languages.
￼
Let's take a closer look at these languages and their commands starting with data definition language or DDL.
DDL as the name says helps you define data in your database. But what does it mean to define data? Before you can store data in the database. You need to create the database and related objects like tables in which your data will be stored. For this, the DDL part of SQL has a command named create. Then you might need to modify already created database objects. For example, you might need to modify the structure of a table by adding a new column. You can perform this task with the DDL alter command. You can remove an object like a table from a database using the DDL drop command. 
￼
￼
￼
Data manipulation language or DML commands are used to manipulate data in the database, like inserting updating or deleting data. Most crude operations fall under DML. To add data to a table, you can use the insert command. This command lets you specify the fields to add data too along with the values to be inserted. If you need to edit data that's already inserted into a table, just deploy the update command. And you can specify data to be removed by using the delete command.

So far, you've learned how to add database objects and manage data within them. So how do you read or retrieve that data? To read data stored in a database, you can use data query language. DQL defines a select command to be able to retrieve data. Select lets you retrieve data from one or multiple tables letting you specify the data fields that you want based on preferred filter criteria.
￼
And finally, you can also use DCL or data control language to control access to the database. For example, using DCL commands, you control access to data stored in the database. Grant and revoke DDL commands are used to give users access privileges to data, and to revert access privileges already given to users. You should now be familiar with how SQL acts as the interface between the database and its users, and you should also be able to identify SQL operations and sub languages.
￼
The biggest advantage of SQL is that it requires very little coding skills to use, is just a set of keywords. It's a very developer or user-friendly language. SQL's interactivity makes it even more user-friendly because it lets developers write complex queries in a short space of time. If you need to work with relational databases for your next project, you just need to know what keywords to use and when. SQL is also a standard language that can be used with all relational databases like MySQL. This also means that there's a lot of support and information available.
SQL can run on any computer once you've database software installed. SQL is also a portable language. Once you write your code, it can then be used in any hardware, on any operating system or platform wherever you need. If you write SQL code in a desktop and then move it to a production server environment, it will run the same in both locations. Also, SQL is a comprehensive language that covers all areas of database management administration. For example, it allows you to create databases, insert, update, and delete data, retrieve and share data among multiple users and manage database security. The final advantage of SQL is that it lets database users process large amounts of data quickly and efficiently. 
ADVANTAGES:
You now know that SQL is a 
simple, 
standard, 
portable, 
comprehensive, and 
efficient language 
that can be used to communicate and work with relational databases.
￼
￼
Just repeat the same steps for each new table you want to add to your database. 
￼
￼
￼
￼
￼

Common SQL Commands:
SQL can be used to perform different types of operations in the database such as accessing data, describing data, manipulating data and setting users roles and privileges (permissions). 
commands(create) vs syntax(create database d)
The SQL Commands are grouped into four categories known as DDL, DML, DCL and TCL depending on their functionality, namely the type of operation they’re used to perform. 

Data Definition Language (DDL)
The SQL DDL category provides commands for defining, deleting and modifying tables in a database. Use the following commands in this category.
CREATE Command
Purpose: To create the database or tables inside the database
Syntax to create a table with three columns:
CREATE TABLE table_name (column_name1 datatype(size), column_name2 datatype(size), column_name3 datatype(size));

DROP Command 
Purpose: To delete a database or a table inside the database. 
Syntax to drop a table:
DROP TABLE table_name; 

ALTER Command 
Purpose: To change the structure of the tables in the database such as changing the name of a table, adding a primary key to a table, or adding or deleting a column in a table.
1. Syntax to add a column into a table:
            ALTER TABLE table_name ADD (column_name datatype(size)); 
      2. Syntax to add a primary key to a table:
            ALTER TABLE table_name ADD primary key (column_name);

TRUNCATE Command
Purpose: To remove all records from a table, which will empty the table but not delete the table itself. 
Syntax to truncate a table:
TRUNCATE TABLE table_name;

COMMENT Command
Purpose: To add comments to explain or document SQL statements by using double dash (--) at the start of the line. Any text after the double dash will not be executed as part of the SQL statement. These comments are not there to build the database. They are only for your own use.   
Syntax to COMMENT a line in SQL: 
--Retrieve all data from a table
SELECT * FROM table_name; 

Data Manipulation Language (DML)
The SQL DML commands provide the ability to query, delete and update data in the database.  Use the following commands in this category.
SELECT Command
Purpose: To retrieve data from tables in the database. 
Syntax to select data from a table:
SELECT * FROM table_name;

INSERT Command
Purpose: To add records of data into an existing table. 
Syntax to insert data into three columns in a table:
INSERT INTO table_name (column1, column2, column3) VALUES (value1, value2, value3);

UPDATE Command 
Purpose: To modify or update data contained within a table in the database. 
Syntax to update data in two columns:
UPDATE table_name SET column1 = value1, column2 = value2 WHERE condition;

DELETE Command
Purpose: To delete data from a table in the database.
Syntax to delete data:
DELETE FROM table_name WHERE condition;
Data Control Language (DCL)
You use DCL to deal with the rights and permissions of users of a database system. You can execute SQL commands to perform different types of operations such as create and drop tables. To do this, you need to have user rights set up. This is called user privileges. This category deals with advanced functions or operations in the database. Note that this category can have a generic description of the two main commands. Use the following commands in this category:
GRANT Command to provide the user of the database with the privileges required to allow users to access and manipulate the database.
REVOKE Command to remove permissions from any user.
Transaction Control Language (TCL) 
The TCL commands are used to manage transactions in the database. These are used to manage the changes made to the data in a table by utilizing the DML commands. It also allows SQL statements to be grouped together into logical transactions. This category deals with advanced functions or operations in a database. Note that this category can have a generic description of the two main commands. Use the following commands in this category:
COMMIT Command to save all the work you have already done in the database. 
ROLLBACK Command to restore a database to the last committed state.
