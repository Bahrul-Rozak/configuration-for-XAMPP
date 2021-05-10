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
```
chmod 755 xampp-linux - * - installer.run 
```

5. Jalankan command instalasi dibawah ini untuk memulai konfigurasi xampp. 
```
sudo ./xampp-linux-*-installer.run 
```

6. Setup Installer

7. Jalankan Server Apache dan MySQL

8. Akses Website dan PHPmyadmin di Browser
```
http://localhost/phpmyadmin 
```




# Note : 
1. lokasi instalasi xampp sebelumnya ada di /opt/lampp
2. Menghapus instalasi xampp bisa menjalankan perintah berikut
[ sudo /opt/lampp/uninstall ]

3. Menghentikan xampp
[ sudo /opt/lampp/lampp stop ]

4. menjalankan kembali 
[ sudo /opt/lampp/lampp start ]

5. Hak akses untuk htdocs

Masuk ke directory Computer/opt/lampp

kemudian klik kanan > open in Terminal
sudo su

chmod 777 -R htdocs/


# MYSQL ACCESS DENIED
1. Jalankan terlebih dahulu [ sudo /opt/lampp/lampp start ]
2. Kemudian buka [ http://localhost/phpmyadmin/ ]
3. Kembali ke terminal dan cek status mysql [ service mysql status ]
4. kemudian stop koneksi mysql [ service mysql stop ]
5. Kemudian restart kembali [ sudo /opt/lampp/lampp restart ]
6. Kemudian nyalakan kembali [ sudo /opt/lampp/lampp start ]
7. kembali ke localhost
8. Enjoy



