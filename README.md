# springbootBackend
After cloning the application
it will automatically initialize the installation of dependencies
after that follow the below steps 


## Database Configuration

To Create a new database >

>>Go to [pgadmin]

>>On the right hand side of the screen you will see [object explorer]

>> Drop down the Server
There you will see two different connection name PostgreSQL which is our server and other is login database

>> Drop down the PostgreSQL 17 menu 
>> Databases >> right click >>Create >> Database >> name it {__} >> expand it >> Schemas >> Tables
 >> Right click >> Create Table OR Query Tool to type Querys >>
 >> Create Table and Columns >> 

//As per my connection
database is userdb 
user is postgres
password is mypass


To connect to the database.

1. go to src >> resources>> Application.yml
   password: mypass123
    url: jdbc:postgresql://localhost:5432/userdb
    username: postgres

    change as per your database


after connection 

Go to src >> test\java\com\exmaple\demo >> DemoApplication.java
Locate this class 
above it you will see a Run|Debug option if not call me i will explain 

public static void main(String[] args) {
		SpringApplication.run(DemoApplication.class, args);
	}

after running the main method you need to access any browser and 
type 

##localhost:8080

it will rredirect you to signup page

remainig work adding campusDrive.html to the website 