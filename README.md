# Employee-Payroll-System

## Project Background
Our Payroll Managament System able to generate Salary Slip to the employess while basic salary and bonus are updated by admin. To simulate our project in real life, we have developed an Employee Payroll Management System based on our University UCSI University. This system will be developed using Java Programming, SQL as the Database, and MySQL as the Database Management System.

We have created three Graphical User Inteface (GUI) which are Login GUI, Admin GUI, and Salary Slip GUI. The snapshot of each GUI will be shown in System Design.

##System Design

######Flowchart
![EPMS_Flowchart](https://user-images.githubusercontent.com/107078925/173619642-5d0cb751-62ce-4650-82d5-6153cd7ccc31.jpg)

We have used components from Swing and AWT Libraries to design the GUI.

######Login GUI
![loginGUI](https://user-images.githubusercontent.com/107078925/173621876-15a31249-4079-4f12-8963-7b8aac0baca9.jpg)
Login GUI is the first GUI that user will be seeing when he/she runs the application. If the user is an employee, he/she can proceed to check the salary slip provided administrator has updated their salary. If the user is an administrator, he/she shall enter the username and password. If you want to change the password and user, you will need to change it at LoginGUI.java at following lines:

`if (stradmin.equals("admin") && strpass.equals("admin")) {`
'admin' is the username and password in our employee payroll management system

######Admin GUI
![Admin_GUI](https://user-images.githubusercontent.com/107078925/173625287-9f1493db-551e-4eb2-968e-841a06ed5751.jpg)

Admin GUI consists of the following features:
- Add New Employees
- Display Employee Information
- Salary Calculation based on Days and Rate Per Day

######Salary Slip GUI
![Salary Slip GUI](https://user-images.githubusercontent.com/107078925/173625323-59b84938-32c0-4e66-bcf9-12ba8b7e25a8.jpg)

This GUI is used to display Salary to employee after user key in his/her ID in the Login GUI. It has the 'print' button that allow user to print the salary slip to PDF.

Database
All the functions that used to manipulate data in the database are defined in Database.java, change the username and password in the source code to your database's username and password.
`this.connect_db = DriverManager.getConnection(url, "root", "password");`

###Requirements
In order to run this application, you will need to install MySQL and its workbench to create a database to store employees' information. You can use other method to create the database and table, but MySQL workbench is the most convienient to do so. Following picture shows the column name in the employee table.

![column_name](https://user-images.githubusercontent.com/107078925/173625358-01df2941-6d8a-40d4-b436-5898c797b375.png)

##Requirements
- Bryan Keane
- Lim Zhi Min
- Ahmed Rafat
- Kong Ping Hao
