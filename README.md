#Labs7_FormlistPHP

Assalamuallaikum wr.wb Okee sedulur semua balik ke github saya mastio_1836 kali ini kita akan Membuat sebuah program sederhana Program php form list tapi sebelum saya mengupload program tersebut disini juga saya akan menampilkan sebuah program sederhana dari php mau tau simak berikut adalah tampilanya 
Okee sebelum kita membuat program kalian bisa download xampp nya caranya
Persiapan
Untuk memulai membuat kode php, perlu disiapkan web server dan interpreter PHP
terlebih dahulu. Web servar yang kita gunakan adalah Apache 2 dan interpreter PHP 7.
Untuk memudahkan proses praktikum, kita gunakan aplikasi bundle web server yaitu
XAMPP.
Install XAMPP
Unduh XAMPP dari https://www.apachefriends.org/download.html dan pilih versi
portable untuk memudahkan proses installasi. Kemudian extract file tersebut, seusikan
direktorinya (misal: d:\xampp). 
Konfigurasi Web Server
• Konfigurasi Apache
Untuk konfigurasi HTTP server, seperti port yang digunakan akses HTTP, modul
yang diaktifkan, lokasi document root, dll.
Lokasi file: \xampp\apache\conf\httpd.conf
• Konfigrasi PHP
Untuk konfigurasi perilaku engine PHP yang berefek pada keamanan dan performa.
Seperti batas maksimal waktu eksekusi script, batas file yang dapat diupload, error
reporting, dll.
Lokasi file: \xampp\php\php.ini
• Konfigrasi MySql
Konfigurasi server MySQL, seperti administrator user, port, timezone, dll.
Lokasi file: \xampp\mysql\bin\my.ini
# Menjalankan Web Server
Untuk menjalankan web server dari menu XAMPP Control

![Xampp](https://user-images.githubusercontent.com/56244106/117775802-0e857380-b265-11eb-8801-696c6540e433.JPG)

• Uji coba apakah server sudah berkerja dengan baik
http://127.0.0.1 atau http://localhost
Tampil halaman utama XAMPP jika server sudah berkerja dengan baik.
• Dokumen Website
Semua file website tempatkan di direktori: \xampp\htdocs\
• Database MySQL
Direktori: \xampp\mysql\
lalu setelah kita membuat file nya di htdocs caranya buka
> Buka Windows C
> lalu "XAMPP"
> Kemudian Htdocs dan saya mebuat file dengan nama lab7_php_dasar seperti gambar berikut
![folder yang ingin di input](https://user-images.githubusercontent.com/56244106/117776569-eba78f00-b265-11eb-856f-26b49596b36b.JPG)
> Kemudian untuk mengakses direktory tersebut pada web server dengan mengakses URL:
http://localhost/lab7_php_dasar/

PHP Dasar
Buat file baru dengan nama php_dasar.php pada directory tersebut. Kemudian buat
kode seperti berikut.

![input menampilkan hello world](https://user-images.githubusercontent.com/56244106/117778403-c9167580-b267-11eb-98f6-82928f7cacd7.JPG)

Kemudian untuk mengakses hasilnya melalui URL:

http://localhost/lab7_php_dasar/php_dasar.php
![Output Hello world](https://user-images.githubusercontent.com/56244106/117778059-7046dd00-b267-11eb-9db6-b5a25d3e05b0.JPG)

# Variable PHP
Berikut ini  adalah input php yaitu Variable PHP

![input menggunakan variable](https://user-images.githubusercontent.com/56244106/117778545-f400c980-b267-11eb-890a-4baff39cec6f.JPG)

Outputnya

![Output menggunakan Variable](https://user-images.githubusercontent.com/56244106/117778736-26aac200-b268-11eb-95f3-5fc63ce2f236.JPG)

# Membuat Form input
Berikut ini adalah input php membuat form input berikut adalah inputnya

![Form input](https://user-images.githubusercontent.com/56244106/117780041-71790980-b269-11eb-8370-20faae6a8e6b.JPG)

Outputnya

![Output Form input](https://user-images.githubusercontent.com/56244106/117780193-9bcac700-b269-11eb-8dfe-19d1a1a28975.JPG)

# Input Operator
Berikut ini adalah input dari program input yang suda di input ke teks editor

![Input operator](https://user-images.githubusercontent.com/56244106/117780924-4a6f0780-b26a-11eb-8fb3-5bfeb3913caa.JPG)

Outputmya

![Output Operator](https://user-images.githubusercontent.com/56244106/117781013-5fe43180-b26a-11eb-9469-5c6b710be278.JPG)

# Kondisi if
Pengertian Struktur IF dalam bahasa pemograman adalah sebuah struktur logika untuk membuat percabangan alur program. Secara sederhananya, dengan menggunakan struktur IF kita dapat mengatur apakah sebuah perintah akan dijalankan atau tidak tergantung kepada kondisinya.Berikut adalah contoh input dari kondisi if

![input kondisi IF](https://user-images.githubusercontent.com/56244106/117782729-1ac0ff00-b26c-11eb-9b3a-8dcb070a37e1.JPG)

Outputmya

![Output kondisi if](https://user-images.githubusercontent.com/56244106/117782800-2c0a0b80-b26c-11eb-92fb-2d582379afe4.JPG)

# Kondisi Switch
SWITCH termasuk statement yang dapat dipergunakan untuk menyatakan suatu pernyataan kondisional atau bersyarat. Selain SWITCH, kita bisa pula menggunakan IF untuk menyatakan kondisional.
Dalam SWITCH, persyaratan hanya diuji sekali saja. Sedangkan pada IF.. ELSE diuji beberapa kali. Sehingga apabila script Anda sangat kompleks atau banyak menggunakan kondisional, penggunaan SWITCH akan menghasilkan proses yang lebih cepat.
Selain itu, statement yang akan dikerjakan dalam SWITCH bisa kosong atau tidak melakukan apa-apa. 
berikut adalah input phpnya

![Input kondisi Switch](https://user-images.githubusercontent.com/56244106/117786558-d6376280-b26f-11eb-9f87-2146d94ec656.JPG)

Outputnya

![Output swtich](https://user-images.githubusercontent.com/56244106/117786604-e2232480-b26f-11eb-99d6-fcc9f5a2be88.JPG)

# Perulangan For
Struktur perulangan (atau dalam bahasa inggris disebut dengan loop) adalah instruksi program yang bertujuan untuk mengulang beberapa baris perintah. Dalam merancang perulangan kode program, kita setidaknya harus mengetahui 3 komponen, yaitu kondisi awal dari perulangan, perintah program yang akan diulang, serta kondisi akhir dimana perulangan akan berhenti.
Di dalam bahasa pemograman, terdapat beberapa jenis instruksi perulangan, salah satunya: struktur perulangan FOR.
Berikut adalah input perulangan for

![output perulangan for](https://user-images.githubusercontent.com/56244106/117786917-2f9f9180-b270-11eb-888b-b586b6e4e4e3.JPG)

# Perulangan While
perulangan while untuk kondisi perulangan dimana banyaknya perulangan tidak dapat dipastikan pada saat penulisan program.
Misalkan kita ingin membuat program tebak angka, dimana user akan menebak 1 angka dari 1 sampai 10. Untuk kondisi ini, kita tidak dapat mengetahui berapa kali user akan ’mencoba’ untuk menebak angka tersebut. Bisa saja user mencoba sebanyak 1, 5, atau 10 kali sebelum angka tersebut berhasil diterka.
Berikut ini adalah input perulangan while

![input while](https://user-images.githubusercontent.com/56244106/117787208-7097a600-b270-11eb-8839-e66e1ed413c8.JPG)

Outputnya

![Output while](https://user-images.githubusercontent.com/56244106/117787246-7b523b00-b270-11eb-8790-9f1d0232928f.JPG)

# Perulangan Dowhile
Perulangan while dan do-while pada dasarnya hampir sama. Perbedaan terletak pada ’lokasi’ pengecekan kondisi perulangan.
Dalam struktur while, pengecekan untuk kondisi perulangan di lakukan di awal, sehingga jika kondisi tidak terpenuhi, maka perulangan tidak akan pernah dijalankan.
Namun pada perulangan do-while, pengecekan kondisi akan dilakukan di akhir perulangan, sehingga walaupun kondisi adalah FALSE, perulangan akan tetap berjalan minimal 1 kali.
Berikut ini adalah input nya

![input Dowhile](https://user-images.githubusercontent.com/56244106/117787711-e8fe6700-b270-11eb-8d95-cccdda6be1ae.JPG)

Outputnya

![output dowhile](https://user-images.githubusercontent.com/56244106/117787867-0e8b7080-b271-11eb-9f72-a19aef8b2466.JPG)


# TUGAS PRAKTIKUM 
Buatlah program PHP sederhana dengan menggunakan form input yang menampilkan nama, tanggal lahir dan pekerjaan. Kemudian tampilkan outputnya dengan menghitung umur berdasarkan inputan tanggal lahir. Dan pilihan pekerjaan dengan gaji yang berbeda-beda sesuai pilihan pekerjaan dan berikut adalah tampilan source codenya yang sudah di disiapkan di tekseditor
Disini kita bikin sebuah file baru di teks editor kalian lalu save di htdocs kalian kalo saya sama seperti yang diatas foldernya dengan nama index.php atau sesuka kalian yang terpenting menggunakan ".php"
lalu tampilan berikut dari source code nya

![Form list input prak7](https://user-images.githubusercontent.com/56244106/117789107-316a5480-b272-11eb-93b9-8b2d716dcc24.JPG)

Jika kalian sudah membuat seperti pada gambar diatas kalian boleh mengakses file tersebut pada url yang kalian simpan seperti punya saya URL:http://localhost/lab7_php_dasar/praktikum7 Berikut adalah hasil nya

![Output Formlist Prak7](https://user-images.githubusercontent.com/56244106/117789993-1cda8c00-b273-11eb-8ddc-a6e2efbe5c86.JPG)

jika sudah kalian kembali ke tekeditor kalian untuk membuat form untuk memanggil dari formlistnya tersebut berikut inputanya

![input untuk memanggil programnya](https://user-images.githubusercontent.com/56244106/117790127-3ed40e80-b273-11eb-940b-00891a1dc79c.JPG)

berikut adalah hasil dari input program tersebut
![Ouput memanggil PHP](https://user-images.githubusercontent.com/56244106/117790249-5f03cd80-b273-11eb-9fc8-224d2cf53c1a.JPG)

Nah ini adalah hasil dari penggabungan dari formlist dan form untuk koneksinya

![Output Form Listnya](https://user-images.githubusercontent.com/56244106/117790392-8064b980-b273-11eb-9c78-e350e44321a1.JPG)
