# DB

## Definitions
### DB
**Database** is a collection of related data.

### DBMS
**Database Management System** is a software to facilitate the creation and maintenance of a computerized database.

#### Advantages
- **Standardization**.
- Better data **accessibility** and **response**.
- **Shared** data between different users who get different views of the data.
- Enforcing Integrity constraints.
- Improed Daata Quality; because of **Constraints** and **Validation rules**.
- **Consistency** because DB is **shared**.
- Restricting **Unauthorized** access.
- Providing **Backup** and **Recovery**.
- Minimal data **Redundancy** -> Leads to increased data integrity/consistency.
- Program-Data Independence:
    - **Metadata** stored in **DBMS**; so **applications** don't worry about data formats.
    - Data *queries*/*updates* managed by **DBMS**.

#### Disadvantages
- Needs **expertise** to use.
- **DBMS** is expensive; because you need to pay for the licence of the **DBMS** software.
- The **DBMS** may be ***incompatible*** with any other available

**DBMS**.
### Database System
It's the **DBMS** software together with the data itself, or the applications that deal with it. So we can say it's the combination of *DB* and *software*.

## DB users
### Database Administrator (DBA)
They are responsible for **DB** creation, including:
- Set up & create the DB.
- Allocate the Random and Disk memory DB needs.
- Determine the processing power DB needs.
- Set the DB security.
- Enhance the DB performance.
- Backup & Restore the DB.

### System Analysts
They are responsible for covering the gap between the **client** and the **DB designer** through converting the **client** requirements to a **Requirement document**

### Database Designer
They are responsible for converting the **Requirement document** to **Entity Relationship Diagram (ERD)** and using the **ERD** to make **DB Mapping**.

### Database Developer
They are taking the **DB tables schema** and converting it to ***physical DB*** through tools called **Relational DB Management System**.

### Application programmers
They are responsible for creating the **application** that deals with the **DBMS**.

### BI & Big Data Specialist (Data Scientist)
They are responsible for taking the **Data** from **DBMS** and analyzing it.

### End users
They are the **clients** who use the DB directly through *applications* or *reports*.