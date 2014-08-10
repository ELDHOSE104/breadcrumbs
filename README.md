breadcrumbs
===========
How to Setup
============
1. This project runs on CodeIgniter. Download it first: http://ellislab.com/codeigniter
2. Extract the CodeIgniter files to your server folder, and copy (replace if already exists) all files from this repository to the same folder.
3. In the /config folder,
  1. In config.php, enter your "base_url" and "encryption_key", if you intent to change it.
  2. In database.php, fill up hostname, username, password and database name.
  3. In facebook.php, enter your appId and app secret. (Get it from developers.facebook.com/apps)
4. In your phpMyAdmin, create a new database (with the name you entered in config.php), and import the tables.sql file.
5. Your installation should now be ready. To make yourself an admin, first log-in using Facebook, and in the "users" table, change your role to a number >1 (say, 10).
6. Let me know if you face any problems.

License
=======
This project is licensed under GNU GENERAL PUBLIC LICENSE Version 2.
You're free to use this project for any purpose, but you
SHOULD provide the source code of any derivation freely available,
along with the proper attribution to the original project creator.

See the file LICENSE.

online treasure hunt of mace...the trail of breadcrumbs
