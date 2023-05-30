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
### XML To SQL Converter Results Using Python
![image](https://github.com/alis0712/XMLToSQL/assets/62857780/38f169b0-12e8-4b80-bae8-3aa64e20cdb2)

### Database Tables
![sender](https://github.com/alis0712/XMLToSQL/assets/62857780/9d36c9db-0fdd-49e5-92e3-71ec97bd7ef6)

![fruits_Table_xml_to_sql_using_python](https://github.com/alis0712/XMLToSQL/assets/62857780/f454f56f-ec80-4726-a035-df265ae542c6)

![Bank_Customer_Table_xml_to_sql_converter_using_python](https://github.com/alis0712/XMLToSQL/assets/62857780/e01b7fbe-56db-458c-a7a1-bc9d0f64662d)

![Bank_Employee_Table_xml_to_sql_converter_using_pythob](https://github.com/alis0712/XMLToSQL/assets/62857780/8e6fb2f5-7dbe-499b-a008-c24de054b6b1)

![receiver_bank_accounts_details](https://github.com/alis0712/XMLToSQL/assets/62857780/fa036426-9aa2-4cb0-9fc3-adef7a2443a1)

![receiver_bank_employee](https://github.com/alis0712/XMLToSQL/assets/62857780/959d3a58-babd-4d4d-9275-d3506f6983ee)

![receiver_fruits_details](https://github.com/alis0712/XMLToSQL/assets/62857780/760981e1-7cb4-4f46-9dff-b6ff3bf4f3e7)

