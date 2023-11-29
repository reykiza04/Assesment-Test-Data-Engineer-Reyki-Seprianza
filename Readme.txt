Data and Query Task (Basic)
1. Create script to create table for each object
a. Employee
b. PositionHistory
2. Create insert script to inserting data into each table (Employee and PositionHistory)
3. Create query to display all employee (EmployeeId, FullName, BirthDate, Address) data with their
current position information (PosId, PosTitle, EmployeeId, StartDate, EndDate).

kindly check file "Answer.txt"
=================================================================================================================================

ETL, Data Warehouse and Analytics Task
Build and design simple Data Warehouse and analytics data, data source came from 2 different source
1. Employee data, source from Azure
2. Training history, source from GCP (Google Cloud Platform)
Requirement and Details:
1. Azure Employee data is using SQL Server as Database Server. This is database for saving
employment data like their employee number, name, birthdate, position/job etc. Each employee
has one record for their employment data.
2. Training History data is using Google Worksheet as data platform. The worksheet contains
historical data about training that completed by employee. Each employee may have more than
one records for their training history data.
3. Design simple ETL Flow that compile these two data sources into Data Warehouse
4. Design simple report that displays historical training data
5. Design simple dashboard that displays
a. Total employee completed training each month
b. Total training each month

Answer
1. I using my own local host sql to create the database 
2. I using google sheet and make API to get thedata using python (previously i ussing SQL Server Integration System but i have some enviroment issue)
3. Please check "ETL_SCPRIT.ipynb"
4. Please check Power Bi file / Simple_dashboard.pdf
5. Lack of data so i cant make dashboard but kindly check power bi 