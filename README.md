# Employee-Payroll-System

## Project Background
Our Payroll Managament System able to generate Salary Slip to the employess while basic salary and bonus are updated by admin. To simulate our project in real life, we have developed an Employee Payroll Management System based on our University UCSI University. This system will be developed using Java Programming, SQL as the Database, and MySQL as the Database Management System.

We have created three Graphical User Inteface (GUI) which are Login GUI, Admin GUI, and Salary Slip GUI. The snapshot of each GUI will be shown in System Design.

##System Design

###Flowchart
![EPMS_Flowchart](https://user-images.githubusercontent.com/107078925/173619642-5d0cb751-62ce-4650-82d5-6153cd7ccc31.jpg)

We have used components from Swing and AWT Libraries to design the GUI.

###Login GUI
![loginGUI](https://user-images.githubusercontent.com/107078925/173621876-15a31249-4079-4f12-8963-7b8aac0baca9.jpg)
Login GUI is the first GUI that user will be seeing when he/she runs the application. If the user is an employee, he/she can proceed to check the salary slip provided administrator has updated their salary. If the user is an administrator, he/she shall enter the username and password. If you want to change the password and user, you will need to change it at LoginGUI.java at following lines:

'if (stradmin.equals("admin") && strpass.equals("admin")) {'
