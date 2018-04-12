# App

Twitter Clone

This is a singer user twitter clone which is built with the help of Silex framework.


Functionality :

1)	User first lands on the home page where the user can enter the user id and password to log in.

user id: test@mail.com
password: test

2)	The user has an option to post the tweets and tweets are displayed at the bottom.


Instructions for execution : 


1) Database set up :

Execute the attached file silex.sql in the database, so that the entire database with username and password is created along with the tables.

Navigate to bootstrap/app.php and configure as per the database.

#set the below details

		'host' => 'localhost:8889',
		'dbname' => 'databasename,
		'user' => 'username',
		'password' => 'password',
		'charset' => 'utf8mb4'

2) Start the server and navigate on to the port to access the landing page
