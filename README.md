# CREATING-A-NEW-LARAVEL-APPLICATION-SAMPLE-REST-API
This is a sample project showing how to create Rest API using Laravel 8
CREATING A NEW LARAVEL APPLICATION – SAMPLE REST API
Steps:
1.	Open the terminal and CD into your desired directory within WAMP server, for instance:
C:\wamp\www\githubprojects
2.	Type the following command to create new Laravel application:

Composer create-project Laravel/Laravel projectone

3.	CD into the newly created project in the terminal, for instance:

C:\wamp\www\githubprojects\githubprojectone

4.	To run the application, type this:

Php artisan serve
This will output response like this 
Starting Laravel development server: http://127.0.0.1:8000

5.	Open the browser and type the above url.

6.	You can also access the website normally by typing the web address like this:

http://localhost/githubprojects/githubprojectone/public/

7.	To prevent exposing the files in the root directory in WAMP, a little adjustment will be made.
Rename the server.php as index.php and cut the .htaccess in the public folder and paste it into the root directory
