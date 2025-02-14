# 50 Database Concepts Questions for 3rd Year CS Students

1. Q: What is a database?
   A: A database is an organized collection of structured information or data, typically stored electronically in a computer system.

2. Q: Explain the difference between a database and a database management system (DBMS).
   A: A database is the collection of data, while a DBMS is the software that manages the storage, retrieval, and manipulation of data in a database.

3. Q: What is SQL?
   A: SQL (Structured Query Language) is a standardized language used for managing and manipulating relational databases.

4. Q: Describe the difference between DDL, DML, and DCL in SQL.
   A: DDL (Data Definition Language) is used to define database structures, DML (Data Manipulation Language) is used to manipulate data, and DCL (Data Control Language) is used to control access to data.

5. Q: What is a primary key?
   A: A primary key is a column or set of columns in a table that uniquely identifies each row in that table.

6. Q: Explain the concept of a foreign key.
   A: A foreign key is a column or set of columns in one table that refers to the primary key in another table, establishing a link between the two tables.

7. Q: What is normalization in database design?
   A: Normalization is the process of organizing data in a database to reduce redundancy and improve data integrity by dividing larger tables into smaller ones and defining relationships between them.

8. Q: Describe the ACID properties in database transactions.
   A: ACID stands for Atomicity (all-or-nothing execution), Consistency (database remains in a valid state), Isolation (concurrent transactions don't interfere), and Durability (committed changes are permanent).

9. Q: What is a transaction in database systems?
   A: A transaction is a sequence of one or more SQL operations that are executed as a single unit of work, which either all occur or nothing occurs.

10. Q: Explain the difference between a clustered and a non-clustered index.
    A: A clustered index determines the physical order of data in a table, while a non-clustered index creates a separate structure for faster lookups without changing the table's structure.

11. Q: What is a view in SQL?
    A: A view is a virtual table based on the result-set of an SQL statement. It contains rows and columns, just like a real table, but doesn't store the data itself.

12. Q: Describe the concept of database normalization forms (1NF, 2NF, 3NF, BCNF).
    A: These are guidelines for reducing redundancy in database tables. 1NF eliminates repeating groups, 2NF removes partial dependencies, 3NF removes transitive dependencies, and BCNF addresses anomalies resulting from multiple overlapping candidate keys.

13. Q: What is a stored procedure?
    A: A stored procedure is a prepared SQL code that can be saved and reused, allowing for efficient execution of frequently used SQL statements.

14. Q: Explain the difference between OLTP and OLAP systems.
    A: OLTP (Online Transaction Processing) systems manage transaction-oriented applications, while OLAP (Online Analytical Processing) systems are used for data analysis and decision support.

15. Q: What is database sharding?
    A: Sharding is a database scaling technique where data is horizontally partitioned across multiple databases to distribute load and improve performance.

16. Q: Describe the purpose of an ERD (Entity-Relationship Diagram).
    A: An ERD is a graphical representation of entities and their relationships to each other, used to design and visualize the structure of a database.

17. Q: What is a trigger in databases?
    A: A trigger is a special type of stored procedure that automatically executes when a specified event occurs in the database server.

18. Q: Explain the concept of database replication.
    A: Database replication is the process of copying data from one database to one or more other databases, typically for improved availability, fault tolerance, or access performance.

19. Q: What is the difference between a left join and a right join?
    A: A left join returns all rows from the left table and matching rows from the right table, while a right join returns all rows from the right table and matching rows from the left table.

20. Q: Describe the purpose of the HAVING clause in SQL.
    A: The HAVING clause is used in combination with the GROUP BY clause to filter group results based on a specified condition.

21. Q: What is a composite key?
    A: A composite key is a key that consists of two or more columns to uniquely identify a row in a table.

22. Q: Explain the concept of a data warehouse.
    A: A data warehouse is a large, centralized repository of data collected from various sources within an organization, used for query and analysis rather than transaction processing.

23. Q: What is the difference between DELETE, TRUNCATE, and DROP commands?
    A: DELETE removes specific rows and can be rolled back, TRUNCATE removes all rows quickly and can't be rolled back, and DROP removes the entire table structure.

24. Q: Describe the purpose of an index in a database.
    A: An index is a data structure that improves the speed of data retrieval operations on a database table at the cost of additional storage and slower writes.

25. Q: What is a deadlock in database systems?
    A: A deadlock occurs when two or more transactions are waiting for one another to give up locks, resulting in none of them proceeding.

26. Q: Explain the concept of database constraints.
    A: Database constraints are rules enforced on data columns to maintain the accuracy and reliability of the data, such as NOT NULL, UNIQUE, PRIMARY KEY, FOREIGN KEY, and CHECK constraints.

27. Q: What is the purpose of the UNION operator in SQL?
    A: The UNION operator combines the result sets of two or more SELECT statements, removing duplicate rows unless UNION ALL is used.

28. Q: Describe the difference between optimistic and pessimistic locking.
    A: Optimistic locking allows multiple transactions to proceed without locking resources, checking for conflicts at commit time. Pessimistic locking locks resources as soon as a transaction begins.

29. Q: What is a materialized view?
    A: A materialized view is a database object that contains the results of a query, stored as a concrete table that can be updated from the original base tables.

30. Q: Explain the concept of database partitioning.
    A: Database partitioning is the division of large tables into smaller, more manageable pieces called partitions, which can be spread across multiple storage devices to improve performance and manageability.

31. Q: What is a cursor in SQL?
    A: A cursor is a database object that allows row-by-row processing of the result sets, used when it's necessary to perform operations on individual rows returned by a query.

32. Q: Describe the purpose of the COALESCE function in SQL.
    A: COALESCE returns the first non-null value in a list, often used to substitute a default value for null values in a query.

33. Q: What is a self-join?
    A: A self-join is a join in which a table is joined with itself, typically used when a table contains hierarchical or recursive data.

34. Q: Explain the concept of database isolation levels.
    A: Isolation levels define how transaction integrity is visible to other users and systems, ranging from Read Uncommitted (lowest) to Serializable (highest).

35. Q: What is the difference between a natural join and an inner join?
    A: A natural join automatically joins tables based on columns with the same name, while an inner join explicitly specifies the join condition.

36. Q: Describe the purpose of the EXISTS operator in SQL.
    A: The EXISTS operator is used to test for the existence of rows that satisfy a subquery, often used in correlated subqueries.

37. Q: What is a NoSQL database?
    A: NoSQL databases are non-relational databases designed for distributed data stores with humongous data storage needs, offering flexible schemas and scalability.

38. Q: Explain the concept of database denormalization.
    A: Denormalization is the process of adding redundant data to normalize database tables to improve read performance, at the cost of increased storage and potential data inconsistency.

39. Q: What is the CAP theorem in distributed database systems?
    A: The CAP theorem states that it's impossible for a distributed data store to simultaneously provide more than two out of Consistency, Availability, and Partition tolerance.

40. Q: Describe the purpose of the MERGE statement in SQL.
    A: The MERGE statement performs INSERT, UPDATE, or DELETE operations on a target table based on the results of a join with a source table.

41. Q: What is a connection pool in database management?
    A: A connection pool is a cache of database connections maintained so that the connections can be reused when future requests to the database are required, improving performance.

42. Q: Explain the concept of database recovery.
    A: Database recovery is the process of restoring a database to a correct state in the event of a failure, using techniques like logging and checkpointing.

43. Q: What is a correlated subquery?
    A: A correlated subquery is a subquery that depends on the outer query for its values, executed repeatedly for each row evaluated by the outer query.

44. Q: Describe the purpose of the GRANT and REVOKE commands in SQL.
    A: GRANT is used to give specific privileges to database users, while REVOKE is used to take away those privileges.

45. Q: What is the difference between a statement-level trigger and a row-level trigger?
    A: A statement-level trigger fires once for each triggering statement, regardless of how many rows are affected. A row-level trigger fires once for each row affected by the triggering statement.

46. Q: Explain the concept of a data mart.
    A: A data mart is a subset of a data warehouse oriented to a specific business line or team, containing summarized data for analysis.

47. Q: What is the purpose of the EXPLAIN command in database systems?
    A: The EXPLAIN command is used to display the execution plan of a query, showing how the database will execute the query and allowing for query optimization.

48. Q: Describe the concept of eventual consistency in distributed databases.
    A: Eventual consistency is a consistency model used in distributed systems that allows for temporary inconsistencies but ensures that all replicas will eventually converge to the same state.

49. Q: What is a pivot table in databases?
    A: A pivot table is a data summarization tool that can automatically sort, count, total, or average the data stored in a database, creating a new table to display the summarized data.

50. Q: Explain the concept of a temporal database.
    A: A temporal database is a database with built-in support for handling data involving time, allowing querying based on time periods and maintaining a history of data changes.
