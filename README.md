# EuropeanSoccer

*What is this project about?* The team craetad a command line interface for a database using Java and MySQL. The project focuses on genearting a database and likewise an accompaning apllication that is able to support all CRUD operations. 

Course Name : Datanase Design

### Summary of Technical Specifications:

The project focuses on providing all CRUD operations to any signed in user. This means that the application will have to maintain and respect all the constraints of the relational databse. Hence, the application will provide certain levels of error handling in order to avoid SQL errors coming directly from the database. The design of the databse focuses on the use of functions and procedures for all transaction conducted by the application. Moreover, the database handles triggers and events. The trigger and events aim to aid automate some aspects of the maintaince of the database. This means that their objective is to reduced the amount of operations a databse managers needs to conduct in order to maintain the database consistent overtime. The project uses Java's JDBC driver to establish connection between the Java application and the database. 

### Summary of the Databse and Application:

The project is called EuropeanSoccer, this project is a database and application. In this database and application, users will have access to a large range of statistics relevant to all leagues in European soccer. Within those statistics, the project focuses on providing users with the following: match information, rankings of teams within each league, information on coaches and coaches being sacked, the ability to compare teams, the option to vote, and the capacity to calculate individual statistics for a team. The database divides users into two distinct categories: fan or admin. The fan is the main target of the application. In other words, the application is built to provide fans with as much information as possible. On the other hand, the admin is equipped with the tools to manage and administer the database. Both users will interact with the database through the front-end application. 

### How to run the application:

- Download and run the database dump
- Add the JDBC driver to your reference libraries in Java
- Add all the java files (Project.java and Requests.java) to your project file. The file that
contains the application is Project.java
- In your run configuration make sure that the project name is correct and set the main
class to Project
- In the java file Project.java, for the class Project, you will need to review/change the
userName, password, serverName and portNumber. Make sure that each one of these values matches the information for your current connection in the MySQL workbench (if you are running a local connection you will only need to change the password).
- Make sure that the dbName in the Java file (Project.java) matches the database name in the MySQL workbench. The dbName should be "european_soccer" for both.
- Run the application (application should be visible in the console (command line)).
- The application will ask for a user name and then a password. You can log in as admin or as a fan. (The system will determine if you are an admin or fan based on your login
information).
  - To login as Admin: username is admin_susan and password is pencil80
  - To login as Fan: username is ghost_boy1 and password is 122378
  - You can also use any login information found in the database (look into fans table
for logins for fans and look into admins table for logins for admins)
  - If you login in as fan or admin, just make sure you use the user_name and
password (do not use the user_id)
- The system should indicate that login is successful, you should see a message indicating
so. If login information is wrong, you may enter information again. The system automatically prompts you to re enter a password or username (depending on which one is wrong)
-  Depending on your login type (fan or admin) you will be shown a list of options that the user may execute
-  After an option is chosen, you will be shown a second list of options where you will be prompted to choose again. Depending on which option you choose, the system will ask for different types of input information
-  After the execution of a transaction, you will be shown the same list of options again and you may execute another transaction
-  To quit the application, you will have to return to the main menu and enter the corresponding quit option
-  When you quit the application, a message will be displayed confirming so

***There will be a UML conceptual model and logical model of the database included in the repository***
