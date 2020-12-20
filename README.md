__________________________________________

# SQL (Structured Query Language)
I will load practices executed by me related to the course "SQL for Data Science" from EDX. 
It is available at https://www.edx.org/course/sql-for-data-science
This course is part of a Professional Certificate. It is a free course. But it is possible to get certificate if you decide paying US$39/R$ 199.

The purpose of this course is to introduce relational database concepts and help you learn and apply foundational knowledge of the SQL language. It is also intended to get you started with performing SQL access in a data science environment using Jupyter notebooks.

![SQL](https://github.com/RosanaFSS/SQL/blob/main/Data%202.gif)

Below I share my summary

### Module 1 - Introduction to Databases
18 Dec 2020 \
Day**09**  **#60daysofudacity**

_Introduction to databases and relational concepts. Creation of a database instance on the cloud._

- A database is a repository of data.
- A set of software tools for the data in the database is called DBMS (Database Management System).
- RBMS is a set of software tools that controls the data.
- I learned some advantages :+1: of using cloud databases
:heavy_minus_sign: cloud databases can expand an shrink their storage and compute capacities during runtime to accomodate changing needs and usage demands;
:heavy_minus_sign: scalability | ease of use, users can access from virtually anywhere; :100:
:heavy_minus_sign: disaster recovery | data is kept secure through backups on remote servers in case of failure or power outage.

- There are 5 basic SQL commands: Create, Insert, Select, Update, Delete.

- An Entity Relationship data model, or ER data model, is an alternative to a relational data model.
- In the ER model, entities are objects that exist independently of any other entities.
- Entities have attributes which are the data elements that characterize the entity.
- Attributes are certain properties or characteristics of an entity and tell us more about the entity.
- A table is a combination of rows and columns.
- Common data types include characters such as Char and Varchar, numbers such as integer.

- Hands-on Lab | _I created my IBM Cloud account and a provision for a Database instance on cloud with  DB2 Lite Plan._
![SQL](https://github.com/RosanaFSS/SQL/blob/main/Module%201%20%2C%20hands-on%20lab%20-%20provision%20a%20cloud%20hosted%20database%20instance.jpg)

__________________________________________
### Module 2 - Basic SQL
18 Dec 2020
Day09 #60daysofudacity

Basic SQL statements. Write and practiced basic SQL hands-on in a live database.

- SQL Statements are used for interacting with Entities (that is tables), Attributes (that is columns) and their Tuples (or rows with data values) in relational databases.
- SQL statements fall into two different categories
  - DDL, Data Definition Language statements 
    DDL statements are used to define, change, or drop database objects such as tables.
    Common DDL statement types include: CREATE, ALTER, TRUNCATE and DROP.
  - DML, Data Manipulation Language statement
    DML are used for manipulating or working with data in tables.
    
  - Hands-on lab | _ I created a table named PRACTICE1 with Column1 as the Primary Key. Column1 has the NOT NULL constraint added after the datatype, meaning that it cannot contain a NULL or an empty value_.
 ![SQL]( https://github.com/RosanaFSS/SQL/blob/main/Module%202%20-%20hands-on%20lab%20-%20CREATE%20table.jpg)
 
- Hands-on lab | _ I practiced the five basic SQL statements to CREATE tables, INSERT data, SELECT results, UPDATE and DELETE data. 
![SQL]( https://github.com/RosanaFSS/SQL/blob/main/Module%202%20-%20hands-on%20lab%20-%20five%20basic%20SQL%20statements.jpg)

Here is my solution :clipboard: ![SQL]( https://github.com/RosanaFSS/SQL/blob/main/Module%202%2C%20hands-on%20lab%2C%20five%20basic%20queries.txt)

__________________________________________
### Module 3 - String Patterns, Ranges, Sorting, and Grouping
19 Dec 2020
Day**10 #60daysofudacity**

The objectives of this module are :heavy_minus_sign: using string patterns and ranges in SQL queries, :heavy_minus_sign: how to sort and :heavy_minus_sign:  order result sets and grouping data in result sets.

Today I practiced _creating_ tables  ![SQL]( https://github.com/RosanaFSS/SQL/blob/main/Module%2003/Module%2003%20-%20hands-on%2C%20Creating%20Tables.pdf), _loading data_ ![SQL]( https://github.com/RosanaFSS/SQL/blob/main/Module%2003/Module%2003%20-%20hands-on%2C%20Loading%20Data.pdf) and _selecting data_ with queries _on cloud_ ![SQL]( https://github.com/RosanaFSS/SQL/blob/main/Module%2003/Module%2C%20hands-on%20query%20output.pdf) & ![SQL]( https://github.com/RosanaFSS/SQL/blob/main/SQL%20coding).

I really loaded data today, woo-hoo! \
![SQL](https://github.com/RosanaFSS/SQL/blob/main/Module%2003/loading-animations-preloader-gifs-ui-ux-effects-4.gif)


__________________________________________
### Module 4 - Functions, Sub-Queries, Multiple Tables
19 Dec 2020
Day**10 #60daysofudacity**

The objectives of this module are :heavy_minus_sign:  Employ Built-in functions in Queries, :heavy_minus_sign: demonstrate how to write sub-queries and nested selects and :heavy_minus_sign: build queries to access multiple tables

- Most databases come with Built-in Functions.
- These functions can be included in SQL statements, allowing you to perform operations on data right within the database itself.
- Using database functions can significantly reduce :amazing: the amount of data that needs to be retrieved from the database.

- An AGGREGATE function takes a collection of like values, such as all of the values in a column, as input, and returns a single value or null. Examples of aggregate functions include: SUM(), MINIMUM, MAXIMUM(), AVERAGE()
- SCALAR and STRING functions perform operations on individual values. Examples: ROUND(), LENGTH(), UCASE(), LCASE()

- Date and time functions can be used in the where clause.

- Sub-queries or sub selects are like regular queries but placed within parentheses and nested inside another query.

20 Dec 2020
Day**11 #60daysofudacity**

Today I practiced creating the Pet Rescue Tableexecuting a script containing the create table command. Also worked with multiple tables using sub-queries using sub-queries. So there were two hands-on.

![SQL](https://github.com/RosanaFSS/SQL/blob/main/Module%2004/Show%20me%20the%20Data.gif)

Following my practices
###### Built-in Functions hands-on ![ Built-in ](https://github.com/RosanaFSS/SQL/blob/main/Module%2004/Hands-on%20Pet%20Rescue) & ![Built-in](https://github.com/RosanaFSS/SQL/blob/main/Module%2004/Hands-on%20Lab%205.pdf)

###### Sub-queries & multiple tables hands-on ![ Sub-queries ](https://github.com/RosanaFSS/SQL/blob/main/Module%2004/Hands-on%20sub-queries)


__________________________________________
### Module 5 - Accessing Databases using Python
20 Dec 2020
Day**11 #60daysofudacity**

I used Jupyter notebook to connect to databases an then created tables, loaded data, query data using SQL and analyzed data using Python.
- A notebook interface is a virtual notebook environment used for programming.
- Here are some of the advantages of using Jupyter notebooks.
  - **Language of choice**, notebook support for over 40 programming languages including Python, R, Julia, and Scala.
  - **Share of notebook**, notebooks can be shared with others by email, Dropbox, GitHub, and the Jupyter notebook viewer.
  - **Interactive output**, your code can produce rich interactive output HTML, images, videos, LaTex, and customized types.
  - **Big data integration**, you can leverage big data tools such as Apache Spark from Python, R, and Scala, and explore that same data with pandas, scikit-learn, ggplot2, and TensorFlow.
  
- Each database system has its own library.
 
- There is a mechanism by which the Python code communicates with the DBMS.
- The Python code connects to the database using DB-API calls.
- DB-API is Python's standard API for accessing relational databases.

- The two main concepts in the Python DB-API are connection objects and query objects. You use connection objects to connect to a database and manage your transactions. Cursor objects are used to run queries.
 
The **Python code** connects to the database using **API calls**.  

- I learned that it is always important to close connections so that we can avoid unused connections

I have just a connection to a DB2 database on Cloud database from a Python notebook using ibm_db API. 
![IBM_db APIL](https://github.com/RosanaFSS/SQL/blob/main/Module%2005/Module%2005%20-%20Jupyter%20notebook%20hands%20on.jpg)

- Pandas is a popular Python library that contains high level data structures and manipulation tools designed to make data analysis fast and easy in Python.
At he next hands on I established again connection to a database instance of DB2 Warehouse on Cloud from a Python notebook using ibm_db API. Then created a table and inserted a few rows of data into it. Then queried the data. Retrieved the data into a pandas dataframe.
![IBM_db APIL](https://github.com/RosanaFSS/SQL/blob/main/Module%2005/Module%2005%20-%20Creating%20Tables%2C%20Inserting%20and%20Querying%20Data.jpg)

__________________________________________
### Module 6 - Course Assignment
20 Dec 2020
Day**11 #60daysofudacity**

The objectives of this module are demonstrate effective use of formulating SQL queries, demonstrate use of invoking SQL queries from Jupyter notebooks using Python and demonstrate skill in retrieving SQL query results and analyzing data

__________________________________________
