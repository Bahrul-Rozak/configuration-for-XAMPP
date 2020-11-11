# configuration-for-XAMPP

# For Python connection

import mysql.connector

config = {
  'user': 'root',
  'password': '1234',
  'host': 'localhost:3308',
  'database': 'inventory',
  'raise_on_warnings': True,
}

link = mysql.connector.connect(**config)

XAMPP Default
<br>
username : "root"
password: '""
<br>
kalo pakai mamp pro 
username: "root"
password: "root"
