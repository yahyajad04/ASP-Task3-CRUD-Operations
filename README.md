# ASP-Task3-CRUD-Operations
this is a small project the simulates an organization system for employees,
there is a compressed file named Task3CRUD.zip that have all of the project files except the bin file.

This Task was Done using ASPCORE.NET (Identity) 

This project simulates a system for an Admin of a organization that wants to hire employees.
At the begining you should inject the Admin user in the database directly since in our Site you cant register as an admin and thats for security reasons since admins should be choosen, Actually in our system you can regester at all using the site, if you have no account you only can explore our Home,Privacy,and About us Pages, other than that you have to have an account to see the employees information.

Now that the admin got his account in the database correctly (to the tables: AspNetUsers, AspNetUserRoles with his Admin Role, Employees(optional) -- you may face a problem with injecting the User correctly in the AspNetUsers table since the password should be hashed, if that happened you can edit the _LoginPartial file in the shared Views folder and add the regester page and regester the account with the password and then inject the role and after that remove the regester page) he can Login using the site Login Page (enter the Email and Password Regestered with), after you login successfully an Employees option will show on the Navigation-Bar and since you are the Admin you can use the 4 CRUD operations (Create,Read,Update,Delete) and like that you can create employees and give them there information such as Name email password salary Role , and press Create, as soon as create is pressed this employee will become registered as a new user in the system and the email and password entered on creation will be used for the login.

As for the User Role you will see the Employees option in the Navigation Bar but you only can see the Read operations (employees table, each employee Details)

And thats it for this Project.
