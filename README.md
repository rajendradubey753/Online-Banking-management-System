# Onliine-Banking-Management-System RUN PROCESS:
# First You should connect your java ide with JDBC(Java Database Connectivity) Here the full reference of How to connect JDBC with MY SQL : https://www.javatpoint.com/example-to-connect-to-the-mysql-database
# you should create a database with name of "Banksystem" create table signup (formno varchar (30),name varchar (30),fname varchar (30),dob varchar(60),gendar varchar (30),email varchar (60),marital varchar (30),address varchar (30),city varchar(30),pincode varchar (30),state varchar (600));
# create table signup2(form_No varchar (30),religion varchar(30),category varchar(30),income varchar(30),education varchar (30),occuption varchar (30),pan varchar(30),aadhar varchar (30),seniorcitizen varchar (30));
# create table signup3 (form_No varchar(30),Account_type varchar(40),card_No varchar(30),pin varchar(30),facility varchar(400));
# create table login (form_No varchar (30),card_No varchar (50),pin varchar (30)); 
# create table bank(pin varchar(10),date varchar(50),type varchar(20),amount varchar(20));
![Screenshot (14)](https://github.com/user-attachments/assets/36ddd11a-8266-4c07-8141-059baa275ddc)

![Screenshot (15)](https://github.com/user-attachments/assets/b5deda4f-d5fc-47b2-8a12-b71b964f068a)

![Screenshot (17)](https://github.com/user-attachments/assets/b003047e-f9a1-4a63-9938-374fdfb8e552)

![Screenshot (18)](https://github.com/user-attachments/assets/e7962383-dd6d-45db-97dc-d4e6427fbbcb)

# connection= DriverManager.getConnection("jdbc:mysql://localhost:3306/banksystem","root","aadubey"); By default username is already root. 
# you should run login.java file if click new Customer first you get Application form :
# after register you can get Card number and pin number login as exist customer by using Card Number and Pin Number and can see all details of his You can Select your transction like Cash Withdrawl ,Fast Cash,Pin Change, Balance Enquiry,Mini Statement
![Screenshot (23)](https://github.com/user-attachments/assets/e6d9436f-fedd-4b72-a43c-00508c48c47c)

# if you select mini statement then show your latest mini statement 
![Screenshot (24)](https://github.com/user-attachments/assets/d686f8e9-567d-465b-a303-3fbd0df0cdf9)

