# Pharmacy-Management-System #
(DBMS Project)  <br/>
## AIM ##
The main aim of the project is the management of the database of the pharmaceutical shop. This project is insight into the design and implementation of a Pharmacy Management System. This is done by creating a database of the available medicines in the shop. The primary aim of pharmacy management system is to improve accuracy and enhance safety and efficiency in the pharmaceutical store. The aim of this project is to develop software for the effective management of a pharmaceutical store.
<br/>
## OBJECTIVE: ##
- Primary Objective
  - To gain practical experience by modeling a database based on real world problem.
  - To understand how to work on Back-end (MySQL).
- Secondary Objective 
  - To develop the easy management of the medicines (drugs).
  - To handle the inventory details like sales details, purchase details and stock expiry and quantity.
  - To provide competitive advantage to the pharmacy.
  - To provide details information about the stock on details necessary and help locate it in shop easily.
  - To make the stock manageable and simplify the use of inventory in the pharmacy.

### HARDWARE AND SOFTWARE TOOLS: ###
The system services and goals are established by consultation with system user. They are then defined in details and serve as a system specification. System requirement are those on which the system runs.


⚙️ Hardware Requirements:
- Computer with either Intel Pentium processor or AMD processor.
- 1GB+ DDR RAM
- 40GB hard disk drive

💻 Software Requirements:
- Windows/ MacOS/ Linux operating system.
- MySQL server (WAMP or XAMPP or any)

## DESIGN ##
Database Design is a collection of processes that facilitate the designing, development, implementation and maintenance of enterprise data management systems.
It helps produce database systems:
* That meet the requirements of the users.
* Have high performance.

### Architecture Description ###
The design of a DBMS depends on its architecture. It can be centralized or decentralized or hierarchical. The architecture of a DBMS can be seen as either single tier or multi-tier.

### ER-Diagram & Relational Schema ###
![ER Model](https://user-images.githubusercontent.com/60355338/173853335-c4409b73-a935-41c1-aca9-5cc35c8818a9.png)
#### Fig.1 ER DIAGRAM
An entity–relationship model describes interrelated things of interest in a specific domain of knowledge (Refer Fig 1). It is composed of entity types and specifies relationships that can exist between instances of those entity types.

#### Relational Schema: ###
````
1. CUSTOMER (CustID, Name ,Address, Contact No. Name)
2. DRUG_MANUFACTURER (CompanyID, Name)
3. DOCTOR (DoctID, Contact No Name, Specialization)
4. SALE TRANSCATION (Sale_ID Date Employee_ID)
5. PURCHASE (Date Purchase_ID)
6. SELLS (Sale ID,Drug ID,CustID,,Quantity)
7. PRESCRIBES (CustID, DoctID, Drug ID)
8. DRUG (Cost_Price, Drug ID,Name, Discount, MRP Company_ID ,Expiry)
9. SUPPLIES (Quantity, Purchase_ID,Distributor_ID,Drug_ID)
10. DISTRIBUTOR (Distributor ID, Contact No)
11. EMPLOYEE (Employee_ID, Name, Contact No)
12. No attributes can be NULL in general.
````
## CONCLUSION ##
- Backend for a Pharmacy Management System was effectively and efficiently implemented.
- Any pharmacy using this database can plan ahead for the medicines to be used , purchased and keep a track of retail.
- The project can be collaborated with a Frontend to make a properly functional deployable system.
