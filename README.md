Required Packages:
mysql
flask
flask-mysql


Setup:
1) After installing the required packages, open app.py and replace the username
and password field with your username and password for the mysql server

2) create a directory called /var/lib/mysql-files/ and copy in the .tsv files
for the imdb database as they are shown in load\_data.sql

3) Log into your mysql server and run the sql scripts in this order
  1) db\_create.sql
  2) load\_data.sql
  3) clean\_data.sql
  4) create\_table.sql

4) Now, run app.py and navigate to the link that is output

Video demo:
https://www.youtube.com/watch?v=ESec4mCKu80&feature=youtu.be 
