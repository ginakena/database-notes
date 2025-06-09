# DATABASE NORMALIZATION 
## What is database normalization: 

Database normalization is a process used for data modeling or database creation where you organize your data and tables so they can be added and updated efficiently.

## Why is database normalization important: 
Normalization plays a crucial role in database design. Here are several reasons why it’s essential:

* Reduces redundancy: Redundancy is when the same information is stored multiple times, and a good way of avoiding this   is by splitting data into smaller tables.
* Improves query performance: You can perform faster query execution on smaller tables that have undergone normalization.
* Minimizes update anomalies: With normalized tables, you can easily update data without affecting other records.
* Enhances data integrity: It ensures that data remains consistent and accurate.

## Types of Normalization in DBMS:  

![alt text](./norm.PNG)

 ** 1.  First Normal Form (1NF):
 Ensures that the database table is organized such that each column contains atomic (indivisible) values, and each record is unique. This eliminates repeating groups, thereby structuring data into tables and columns.

 ** 2.  Second Normal Form (2NF):
 It requires all non-key attributes to be fully functional on the primary key.What this means, is that there should be a direct relationship between each column and the primary key, and not between other columns.

 ** 3. Third normal Form (3NF): 
  Extends 2NF by ensuring that all non-key attributes are not only fully functional on the primary key but also independent of each other. This eliminates transitive dependency.
 
 ** 4. Boyce-Codd Normal Form (BCNF): 
 A refinement of 3NF that addresses anomalies not handled by 3NF. It requires every determinant to be a candidate key, ensuring even stricter adherence to normalization rules.

 ** 5. Fourth Normal Form (4NF): 
 Addresses multi-valued dependencies. It ensures that there are no multiple independent multi-valued facts about an entity in a record.

 ** 6. Fifth Normal Form (5NF):
 5NF is the highest normalization level that addresses join dependencies. It is used in specific scenarios to further minimize redundancy by breaking a table into smaller tables.


