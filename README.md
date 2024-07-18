install python
then on cmd - pip install Flask Flask-MySQLdb
pip install pyarrow
pip install pandas
pip install pysqlite3 or pip install db-sqlite3
create database hospital_db
Then create tables patients and doctors - given in database file

for running the code -  
go to vs code
then run DataScript.py
then run arima.py - its the traditional way of querying databses
then run optimized.py - apache arrow is used to query database

for large database you will see optimized.py requires less memory and it's fast as compared to arima.py


