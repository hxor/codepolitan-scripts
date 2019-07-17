# PHP Tips Trick

### Learning Composer

#### Apa itu Composer?

- Apa itu composer ?

  Management Dependency di PHP yang memungkinkan kamu untuk menggunakan library, menginstall dan mengupdate secara mudah untuk project PHP yang kamu buat.

- Apa yang dilakukan oleh Composer?

  1. Dapat dengan mudah menginstal libraries (packages) pada project PHPmu [*Composer dapat melakukan install, update dan mengatur library (sering disebut juga sebagai package) dalam project PHP yang kamu buat.*]
  2. Mengatur Ketergantungan Library [*Karena project kamu menggunakan package, tentu berakibat akan ketergantungan dengan package yang kamu install. Jadi sebagai alat untuk mengatur package PHP, composer memiliki peran sebagai berikut*]
  3. Mengatur dan Memperbarui Package [*Setiap package biasanya akan mengalami perkembangan atau update secara berkala. Bagaiaman jika kita menggunakan versi tertentu dan ingin menginstall lagi di lain project dengan versi yang sama, sedangan packagenya sudah update ? menggunakan composer akan lebih mudah menentukan versi mana yang akan diinstall*]
  4. Mempermudah mencari package yang ingin digunakan [*Karena banyak sekali package yang ada untuk project PHP, baik itu di github atau sumber lainnya, maka Composer ini bertugas untuk mencari daftar package yang tersedia. Kemudian dapat kita install, update atau sesuai kebutuhan dari project kita*]

- Dan composer sendiri adalah

  1. Command-line Tool [*Dan secara teknis Composer adalah alat atau software berbasis command-line untuk mengatur dependency project.*]
  2. Dependency Manager: NPM, NuGet, etc [Bekerja seperti dependency manager pada umumnya]
  3. Otomatis menginstall package dari Packagist.org, etc. [Composer memiliki repository online, dan kenapa pada saat menggunakan composer harus online. Sebab akan mendownload package yang bersifat open source dari Packagist.org. Di sana kita juga bisa melihat terdapat package apa saja yang sering digunakan.]

- Cara kerja composer

  1. Memulai untuk menggunakan composer pada project dengan cara menginstallnya [Kamu install composer pada project yang akan digunakan]
  2. Pasang library atau package [Beri tahu composer untuk menginstall suatu library yang akan digunakan dalam project]
  3. Dapat menggunakan Library dan Package dalam project PHP kita [dan Composer akan berikan package yang kamu install untuk digunakan]
  4. Menkonfigurasi project pada saat dipindah tempat. [Composer akan memilih secara otomatis package mana yang akan digunakan, sehingga pada saat di unggah ke penyimpanan GitHub contohnya. Maka tidak akan dibawa seluruh librarynya. Hanya project kita saja.]
  5. Menginstall Kebutuhan Package yang ada dalam project dari hasil migrasi.



#### Cara Install Composer

#### Cara menggunakan Composer

#### Cara mencari Package/Library

- Lihat Packagist.org
- Banyak package yang bisa dicari
- Terdapat informasi cara install, source code, author, versi package
- dapat memilih versi package yang akan di install menggunakan composer
- Cara terbaik mencari package, googling dlu mana yg jadi rekomendasi atau yg dibutuhkan. baru liat packagist.