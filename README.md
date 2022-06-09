# Guide for the Laragon Apps

[![Code-Igniter](https://img.shields.io/badge/CodeIgniter-%23EF4223.svg?style=for-the-badge&logo=codeIgniter&logoColor=white)]()
[![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white)]()
[![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white)]()
[![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)]()

## Using to switch version on Apache, PHP and MySQL

Untuk menjalankan versi lain dari Apache, PHP dan MySQL dalam satu OS ketika kita membutuhkan suatu program server yang berbasiskan web. Misalnya lokal servernya dijalankan dengan dua buah aplikasi **XAMPP** dan **Laragon** maka hanya ada satu yang boleh berjalan dalam satu waktu tidak boleh keduanya untuk menghindari crash antara aplikasi yang satu dgn lainnya.

Jika ingin menjalankan aplikasi dengan port lainnya seperti **CodeIgniter** dalam Laragon maka harus dijalankan command **php spark serve** di dalam terminal yang tersedia didalamnya.

## Knowing code on filename

**PHP**  versi yang kita mau misalnya **7.4.30** maka kita akan mencari di [PHP v.7.4.30](https://windows.php.net/downloads/releases/) dan akan mendapatkan file **php-7.4.30-Win32-vc15-x64**

**Apache** akan dilihat dari nama file yg didapatkan diatas **php-7.4.30-Win32-vc15-x64** yaitu bagian **vc15** dan itu adalah versi yang kita cari misalnya yng didapatka adalah **httpd-2.4.54-win64-VC15** yg didownload di [Apache V15](https://www.apachelounge.com/download/VC15/#google_vignette)

**HeidiSQL** adalah aplikasi yang mengatur mySQL dari server yang aktif untuk XAMPP dan Laragon akan mendapatkan hasil yang berbeda tergantung server mana yang aktif