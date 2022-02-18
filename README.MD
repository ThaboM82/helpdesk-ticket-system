Features of Complete Helpdesk Ticketing System

Create & manage tickets
Attach files to tickets
Receive email notifications on each ticket response
Organize tickets by status
Organize tickets by label
Organize tickets by department
Assign specific users to each department
Assign a priority to each ticket
Manage canned responses and add them to ticket responses
Manage users & user roles
Set settings from visual interface
Translate the strings from visual interface

Requirements
PHP >= 7.3 or PHP >= 8.x
MYSQL => 5.7 or MariaDB => 10.2.7
BCMath PHP Extension
Ctype PHP Extension
Fileinfo PHP extension
JSON PHP Extension
Mbstring PHP Extension
OpenSSL PHP Extension
PDO PHP Extension
Tokenizer PHP Extension
XML PHP Extension

Installation
Installation steps:

Upload the project folder to your server using File Manager on CPanel (or any panel you are using). In my case it’s called “laravel-app"



Now go inside the folder and change the permissions of the application folders, storage and bootstrap/cache to 775 by right clicking on them and choosing “change permissions“

Then go to sub-domains and create a new sub-domain. The document root should points to the public folder of the project. In our case it’s /home/democom/laravel-app/public.



The sub-domain will be as the following:
http://laravel-app.example.com

Now to go phpMyAdmin or the database manager you have and create a new database called
laravel-app

The installation wizard allows you to configure the system without having to edit the configuration file or execute any command from the terminal.

To access the installation wizard, simply access the application through the browser.
The server is verified to meet the system requirements.
It is also verified that the folders have read and write access.
The access data to the database will be requested to verify the connection and perform the migration of the tables.
The application has been installed correctly, you can access it with the default user data.
The installation wizard is disabled and is no longer accessible after installation is complete. The software is ready to use.
