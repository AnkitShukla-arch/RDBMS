## Types of Database Models-:
1.Hierarchial Database-: Data organized in tree structure 
                         one to many relationship
                         each child has only one parent 
ex-: organization strucutre

---

2.Network Database-: data organized as graph 
                     supports many to many relationships
                     child can have multiple parents 
ex-: organisation activity 
     telecom networks
     transports network 

---

3.Relationship Database Models: Data stored in tables 
                               Rows=Columns
                               Columns=Attributes

ex-: Mysql,oracle,MIcrosoft SQL Server

---

4.Object Oriented Database Model: Data is stored as objects, not tables
                                  These databses are designed to handle complex data structures such as 
FEATURES-: Objects
           Classes
           Inheritance
           Encapsulation 
ex: ObjectDB

---

5.Object Relational Database Model: Table based structure
                                    combination of relational+object oriented 
                                    data is still in tables 
                                    also supports complex data types and object concepts 
ex: PostgreSQL , Oracle 

---

6.Cloud Databases: A cloud database operates in a virtual envionment hosted on cloud computing platforms.
                    It is designed for storing,managing,and executing data over the internet, providing flexibility and scalability.
ex: Amazon Web Services 
    Google Cloud Platforms 
    Microsoft Azure 

---

## Types of Keys-:

1) Super Keys: Set of one or more columns that uniquely identify any row within a table .
  
2) Candidate Keys: A candidate key is a minimal set of columns (attributes) in a database table that can uniquely identify each record, serving as a potential choice for the primary key.
  
3) Composite Keys: A composite key is a primary key in a database formed by combining two or more columns (attributes) that, together, uniquely identify each record (row) in a table, even if individual columns have duplicate values.

4) Primary Key: Uniquely identifies each record in a table; it cannot contain NULL or duplicate values. Only one is allowed per table.

5) Foreign Key: A field in one table that links to the primary key of another table, establishing a relationship and ensuring referential integrity.

6) Alternate Key: A candidate key that was not selected as the primary key.

7) Unique Key: A constraint that ensures all values in a column are distinct, similar to a primary key, but it allows a NULL value.

8) Surrogate Key: An artificially generated identifier (usually numeric) with no business meaning, often used when no natural candidate key is suitable.

---

## E-R Model Concepts-:

1) It is a conceptual framework used to represent the data and relationships in a database .It helps in designing a database by defining entities , their attributes , and the relationships between them.

2) It represents database schema graphically and can be easily converted into relational tables.
  
3) They provide a standardized approach to visulaize data relationship and structures.

4) They model real-world objects , making it easy to visualize data structures.

5) E-R diagrams are easy to understand even for non-technical users.


# COMPONENTS OF AN ER DIAGRAM-:

1) Entities: Objects or things in the real world that are distinguishable from other objects. (SYMBOL-: Rectangle box)
2) Attributes: Characteristics or properties of an entity. (SYMBOL-: Ellipses) 
3) Relationship: It shows the connections between the entity and the attribute. (SYMBOL-: Diamonds)


    
    
     

