# XMLToSQL
XML To SQL Converter Using Python

### The purpose of this project is to apply the XML data management technologies to a real life application. The application project requires implementation of a real life data exchange application using XML. Typically in such an application there will be two databases: a sender database and a receiver database. 

### The application will convert the XML data stored in the sender database to relational format (this is called publishing data), and send the relational data to the receiver database. The receiver database needs to store the received data in structured format (i.e. in tables). The receiver database will also provide several query features that allow users to ask queries over the stored data.  Figure 1 shows the architecture of the project.

![image](https://github.com/alis0712/XMLToSQL/assets/62857780/9f7f50e4-84f0-4115-945c-57222ffddf3e)

### I assumed the following: 

### Assumptions:
### 1.	The sender and receiver databases can be simulated in the same database.
### 2.	The application will read the newly inserted data from the temporary table, and insert it into the receiver’s database. 
### 3.	The XML data should be a well-formatted version (i.e. no errors).

### The detailed requirements of the project were to do as follows: 
### 1.	The sender database is recommended to use a PL/SQL procedure to retrieve XML data from the sender table and store the converted data in structured format. 
### 2.	The receiver database needs to contain at least 2 tables. Since the focus of this project is on XML, it is not recommended to create too many tables.
### 3.	The receiver database contains at least 5 rows per table.

### Results 
