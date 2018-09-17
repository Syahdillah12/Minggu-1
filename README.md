# Workshop
Minggu-1
LANGKAH – LANGKAH MENGINSTAL PYTHON DI WINDOWS 10
      Pada kesempatan kali ini, saya akan mencoba bagaimana memasang intrepreter atau wadah belajar python pada perangkat yang digunakan coder. Disini saya menggunakan sistem operasi windows 10.
1.	Langkah pertama yang kita lakukan yaitu dengan mendownload python, disini saya menggunakan versi terbaru 3.7.0 (64 bit). Bisa di download pada link di bawah ini ; 
 https://www.python.org/downloads/

 

2.	Setelah proses download selesai, kita coba install dengan cara (run/double klik seperti biasa). 
 

3.	Pada tahap ini pengguna dihadapkan pada 2 pilihan installasi.
 
Install Now
Pada pilihan install now pengguna akan menginstall langsung python tersebut pada direktori default yaitu :
C:\Users\UserWindows\AppData\Local\Programs\Python\Python37;

Customize Installation
Pada pilihan customize installation pengguna akan menginstall python dengan pilihan kustomisasi  terhadap lokasi installasi dan beberapa fitur di dalamnya.

4.	Pada tahap ini adalah pemilihan fitur python yang akan di installkan pada perangkat kita nantinya.
 

Documentation
Pada proses instalasi akan disertakan file dokumentasi pendukung.
pip
Pada proses instalasi akan disertakan paket manager yang dapat di download dan diinstallkan pada python.
tcl/tk and IDLE
Pada proses instalasi akan disertakan tcl/tk dan IDLE development environment semacam wadah pengembangan pada python.
Python test suite
Pada instalasi akan disertakan library-library standar
py launcher
Pada installasi akan disertakan laucher untuk memulai menjalankan python.
5.	Pada tahap ini adalah pemilihan pengaturan lainnya seperti instalasi di semua pengguna, pembuatan shortcut, penambahan path variabel python, lokasi folder instalasi dan lain-lain. Setelah itu klik tombol Install.
 
6.	Proses instalasi pun sedang berjalan. Mohon ditunggu..!!
 

7.	Proses instalasi python berhasil. Klik tombol Close untuk menutup jendela ini.
 

8.	Jika dibutuhkan kita dapat mengatur environment variables pada windows secara manual. Buka system properties (Klik kanan My Computer -> Pilih Properties -> Pilih Advanced System Settings -> Pilih  Environment Variables pada tab Advanced).
 
9.	Pada sytem variables kita dapat menambahkan, mengubah ataupun menghapusnya.Disini kita mencoba mengubah variable name Path dan menambahkan variable value berikut pada akhir baris :
 
# Jika pada instalasi python memilih direktori default. C:\Users\UserWindows\AppData\Local\Programs\Python\Python37; C:\Users\UserWindows\AppData\Local\Programs\Python\Python37\Scripts; 
# Jika pada instalasi kita mengkustomisasinya ke direktori lainnya. 
C:\Program Files\Python37; 
C:\Program Files\Python37\Scripts;
 
Setelah menambahkannya pada akhir baris, Klik OK untuk menyimpannya.
10.	Jika kita ingin memisahkan nama variabel baru, maka klik tombol new dan isikan sesuai kebutuhan. Misalnya kita ingin membuat nama variabelnya PYTHON_PATH dan isikan juga nilai variabelnya seperti langkah sebelumnya.
 
11.	Sekarang setelah semuanya di konfigurasi, mari kita membuka program python.
 
12.	Akan terlihat jendela aplikasi command line interface dari Python.
 
13.	Lalu kita coba membuat sebuah output "Hello World" dan lihat hasilnya. Sekarang python dapat dijalankan, seperti yang terlihat pada gambar dibawah.
 

Proses instalasi “PYTHON” pada windows 10 telah selesai..


