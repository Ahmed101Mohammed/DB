# DB Life Cycle
## Analysis of business requirements
The **System Analyst** talks with the client and produces a **Requirement document**.  
The **system Analyst** is somebody with good experience in the field, that a **Business** interest in.  
The **System Analyst** covers the gap between the **Client (Business)** and the **Developer (Engineering)**.  
The **Requirement document** is a good documentation for the *business* requirements, so we can take this documentation, and start to ***Design*** the DB.  

## Designing the DB
The **DB designer** takes the **Requirement documentation** and converts it to an **Entity Relationship Diagram (ERD)**.  
*Entity* is the object that I will store data about, it's not a **table**: So if I have a system with teachers and students, and courses. So I have 3 entities, even if I create 100 tables to make a relation between them.  
The **Entity** should have a relation with other *entities*, not with all of them, but it has at least one relation.
The same **Requirement document** can produce multiple **ERDs**; So the **DB designer** needs to communicate more and more with the **System Analyst** until sure that he/she get the suitable **ERD**.

## DB Mapping
It's a set of rules that a **DB designer** implements on the **ERD** and produces the actual **DB tables schema**.  
**Requirement document** can produce multiple **ERDs** but these multiple **ERDs** can produce one **DB tables schema** because it's a fixed, known rules.  
In the **DB Mapping** phase, you can't change the **ERD**.

## DB Implementation
The **DB developer** takes the **DB tables schema** and converts it to ***physical DB*** through tools called **Relational DB Management System**.  
 
**Relational DB Management System (RDBMS)** it's a set of tools you can use to implement, manage, and execute queries.  
Example of **RDBMS**:  
- SQL Server.
- Oracle.
- MySQL.
To deal with **Relational DB Management System**, we need to learn a **DB language** called **Structured Query Language(SQL)**.  
When **RDBMS** is installed on your device, you can call your device as a `DB Server`.
   
One of the most important characteristics of DB, that it's a *shared DB*. That means that multiple devices can communicate with the same db, if 2 devices communicate with what expect as same db that contain the same data, and they not include the same data, this is called **inconsistance DB**; So we expect also that the **DB** is also *centerlized* this mean that it exist in one location. So for the system, there is just one **DB Server** that all devices communicate with.  

## Applicatin
The **Application programmer** who builds the **application** that uses the **DB** that was already implemented by the **DB developer**.  
The device that stores the **Application** is called the **Application server**.  

The applications can deal with DBs through libraries that communicate with **RDBMS** using *drivers*.  
The application can be any type of application, it's just a **GUI** for the DB, so we can have multiple applications that all deal with the same **DB**. because they are separate from each other.  

## Client
He is the end user who connects to the **Application Server** to use the application, and the Application communicates with the **DB Server** to deal with the **DB**.