# Expense_Tracker
The Expense Management website is a web-based platform designed to help individuals and businesses manage their expenses efficiently. With the ever-increasing demand for effective expense management, this platform offers a streamlined solution that simplifies the process of tracking, categorizing, and analyzing expenses.
Steps to execute the code:-
1)Download the xampp control panel in your system which is a open source web-server solution. It is used for web-application testing on a local host web server.
2)After downloading the xampp control panel in your c-drive. Upload all the code files inside the htdoc folder which is present in xampp folder.
3)Create the database according to the sql file.
4)Connect your database to the code in the config.php file:
<?php
session_start();
$con=mysqli_connect('localhost','root','','expense');
?>
5)Now open your browser and search: localhost/Your_folder_name/index1.php
