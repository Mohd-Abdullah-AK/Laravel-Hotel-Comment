# Laravel-Hotel-Comment
This Project is made by using Laravel 5.3 framework. In this User can view numbers of Hotels List and Give comments.

# Author | Mohd Abdullah
> This is a Test Project containing migration and db:seeds for fake values also on for user table
> For Admin Access your mail :admin@test.com & Password : 123456

# Steps for install
1. Download using git url or manually from the source.
2. Place it on your local directory
3. Now make a database (i am using mysql) in your phpmyadmin.
4. Name your database what you want (by Default it is 'dbtest' with username 'root' and password= '').
5. if you change your DB name then go to config\database.php and change it databse name and user with yours.
6. After this open your cmd | and navigate your root folder where you install the project
7. run the following commands | php artisan migrate | To install all migrations.
8. Now run the seed command   | php artisan db:seed | To install all seeds present in the migration.
9. Now run the command        | php artisan serve   | and open your browser with url http://localhost:8000/
10. Enjoy.
