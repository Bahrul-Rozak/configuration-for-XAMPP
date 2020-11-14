# configuration-for-XAMPP

# For Python connection Database

import mysql.connector

config = {
  'user': 'root',
  'password': '1234',
  'host': 'localhost:3308',
  'database': 'inventory',
  'raise_on_warnings': True,
}

link = mysql.connector.connect(**config)

# XAMPP Default

username : "root"
password: '""

kalo pakai mamp pro 
username: "root"
password: "root"


# Install XAMPP di Ubuntu Simple
1. Unduh File Xampp untuk Linux

2. Buka Terminal

3. cd Downloads

4. Selanjutnya ubah permission file xampp menjadi 755 dengan menjalankan perintah
   [ chmod 755 xampp-linux - * - installer.run ]

5. Jalankan command instalasi dibawah ini untuk memulai konfigurasi xampp. 
	 [ sudo ./xampp-linux-*-installer.run ]

6. Setup Installer

7. Jalankan Server Apache dan MySQL

8. Akses Website dan PHPmyadmin di Browser
		[ http://localhost/phpmyadmin ]




# Note : 
1. lokasi instalasi xampp sebelumnya ada di /opt/lampp
2. Menghapus instalasi xampp bisa menjalankan perintah berikut
[ sudo /opt/lampp/uninstall ]

3. Menghentikan xampp
[ sudo /opt/lampp/lampp stop ]

4. menjalankan kembali 
[ sudo /opt/lampp/lampp start ]
