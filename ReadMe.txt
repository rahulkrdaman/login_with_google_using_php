Author: Rahul
Author Email: rahulkrdaman@outlook.com

This project helps web developers to implement the user registration with Google account using PHP at their web application. Also, the user information is stored in the MySQL database.

============ Installation Instructions ============
1. Create a database (for example, demodb) at phpMyAdmin and import the "SQL/users.sql" file into this database.

2. Open the "config.php" file in a editor: 
===> Specify the database host (DB_HOST), username (DB_USERNAME), password (DB_PASSWORD), and name (DB_NAME) as per your MySQL database credentials.
===> Specify the Google Client ID (GOOGLE_CLIENT_ID), Client Secret (GOOGLE_CLIENT_SECRET), and Callback URL (GOOGLE_REDIRECT_URL) as per your Google API Console Project credentials.

3. Open the index.php file in the browser and test the Google Login functionality.
