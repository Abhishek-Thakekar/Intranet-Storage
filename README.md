The project is to make an offline storage system like drive with a login system.To use the project, do the following:

Download all the files and folders in the repository as it is and copy all of it in a suitbale folder( preferably in F drive).
Install node.js and install all dependencies by entering this in command line - npm install
Edit updown.js and passport.js file to use your database that is in your pc ( Mysql database). The database schema is :
+--------------+--------------+------+-----+-------------------

| Field | Type | Null | Key | Default

+--------------+--------------+------+-----+-------------------

| name | varchar(20) | NO | PRI | NULL

| email | varchar(30) | NO | UNI | NULL

| userPassword | varchar(100) | NO | | NULL

| date | timestamp | YES | | CURRENT_TIMESTAMP

+--------------+--------------+------+-----+-------------------

Change directory in command line and execute "node mainnodefile" in the directory in which all downloaded files and folders reside.
Now you can visit localhost in your browser with port 8000 and use the website.
