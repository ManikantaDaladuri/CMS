# CMS
Content Management System

### Requirements 

- PHP 5.3 or higher recommended 
- MySQL DB
- Ability to write .htaccess file for apache mod_rewrite

### Installation
- Upload Content Management to the directory of your choice.
- Import MySql Db file to your database software (E.g : Php_My_Admin )
- Configure connection to your database and server by modifying connection.php file
- Navigate to the installation in your browser
- Done :)

### Main Features

- Multiple user access:  Allows multiple type of users to login 
- Functional Admin panel:  Allows all admins to manage their content properly with admin panel 
- CRUD functionalities:  Allows all users to create,read,update and delete their content in a managed format 
- Profile update option:  Allows users to update their profile/account details  
- Treading news updates:  Allows user to view all trending news around the world (using google news api) 
- Search news:  Option for search all content 
- Secure registration and login option for users

### To-Do  list
- Add pagination for news post display
- Add various category for news post
- Add comment section for each post
- Add login with facebook and google+ option
- Add forget password recovery option for users

### Does:
1st Step: Extract file

2nd Step: Copy the main project folder

3rd Step: Paste in xampp/htdocs/

4th Step: Open a browser and go to URL “http://localhost/phpmyadmin/”

5th Step: Then, click on the databases tab

6th Step: Create a database naming “latest” and then click on the import tab

7th Step: Click on browse file and select “NEWSBUZZ.sql” file which is inside the “db” folder

8th Step: Click on go.

After Creating Database,

9th Step: Open a browser and go to URL “http://localhost/Content-Management/”
