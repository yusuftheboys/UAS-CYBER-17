# UAS-CYBER-17
TUGAS UAS PENGUJIAN PENETRASI JARINGAN SERKA YUSUF

TUGAS UAS A3 2022 INJECTION (OWASP 10 JUICE SHOP)

Laporan.
	SQL Injection (SQLi) merupakan jenis serangan injeksi yang memungkinkan untuk mengeksekusi statement SQL yang berbahaya. Statement yang digunakan ini dapat mengontrol server database di belakang aplikasi web.
	Hacker dapat melakukan otentikasi dan otorisasi halaman web atau aplikasi web dan mengambil konten dari seluruh database SQL. Mereka juga dapat menggunakan SQL Injection untuk menambah, mengubah, dan menghapus catatan dalam database.Serangan SQL Injection ini dapat menarget semua website yang memanfaatkan SQL database, seperti MySQL, PostgreSQL, SQL Server, dan lainnya.

A.	Download OWASP
Mengunduh rilis terbaru OWASP Juice Shop dari halaman resmi Github.
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/fbcf7a2d-62c8-4222-90a5-6a0020682d97)

Kita perlu mengekstrak isinya karena kita mengunduh file dalam format zip.
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/73b2db64-a9ed-438e-8f63-0a134bfc160e)

B. Install NodeJS Dan NPM
Menyalin Alamat tautan untuk “NodeJS untuk sistem Linux x64” dan menggunakan syntax dibawah ini untuk mengunduh film disistem.
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/4d6b2e0c-727c-4370-a941-aa87258a05f6)

Ekstrak file yang kita download menggunakan perintah tar.
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/550e1402-3a7c-49bd-9b44-b4f5c9fa7c5e)

Menyalin file dari folder yang baru diekstrak ke directori /usr untuk menginstal nodeJS dan NPM disistem kita.
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/8d064e01-2d08-4621-8c27-a66990c0fb9c)

NodeJS dan NPM sudah diinstal kemudian untuk melihat versi dengan perintah sbb:
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/87eecc25-b747-4677-b8a5-932de0bd8769)

C.	Install Ketergantungan Node
Kembali ke OWASP Juice Shope yang di ekstrak. Gunaka cd perintah untuk  mengubah directori ke folder tersebut dan jalankan perintah untuk menginstal paketNode yang diperlukan untuk menjalankan OWASP Juice Shop.
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/95e9c81c-a77b-493b-99f6-0336ecb2b166)

Jalankan perintah dibawah ini untuk menjalankan OWASP Juice Shop
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/066cbdb7-ff08-4b20-85ec-10aa244508b4)
Perintah ini akan memulai aplikasi web pada port 3000. Namun jika ada aplikasi lain yang berjalan pada port tersebut, anda akan melihat opsi untuk menggunakan port lain seperti 3001. 
Lucurkan brouser dengan URL http://localhost:3000/ untuk mengakses aplikasi web.

D.	Bender Login
Bender login adalah login menggunakan akun email alyufa@juice-sh.op menggunakan injection.
1.	Masuk kehalaman login dengan melakukan klik account pada bagian navbar lalu klik login
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/11e39844-b065-45f8-b39b-ae1a9d7b8890)

2.	Selanjutnya pada halaman login ini masukkan email alyufa@juice-sh.op dan dengan password diisi dengan inputan acak.
   	Untuk melakukan injection tambahkan ' -- yang dimana maksud dari inputan tersebut adalah digunakan untuk menonaktifkan
   	argumen query sql setelahnya atau melakukan comment jadi kita dapat menonaktifkan kondisi pengecekan passwordnya.
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/50f76475-18f9-42cb-93f3-e09e23de9085)

3.	Submit login form, maka kita akan berhasil masuk sebagai user bender.
![image](https://github.com/yusuftheboys/UAS-CYBER-17/assets/110083010/ae819d07-584b-470f-9851-9555b9bac22e)
