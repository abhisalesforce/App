# App

Twitter Clone

This is a singer user twitter clone which is built with the help of silex framework.


Functionality :

1)	User first lands into the home page where user can enter the user id and password to login.

user id : test@mail.com
password : test

2)	User has an option to post the tweets and tweets are displayed at bottom.


Insturctions of execution : 


Data base set up :

Execute the attached file silex.sql in the database, so that the entire database with username and password is created along with the tables.

Navigate to bootstrap/app.php and configure as per the database.

#set the below details

		'host' => 'localhost:8889',
		'dbname' => 'databasename,
		'user' => 'username',
		'password' => 'password',
		'charset' => 'utf8mb4'
