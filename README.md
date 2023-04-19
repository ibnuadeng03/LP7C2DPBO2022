# DESAIN DAN PEMROGRAMAN BERORIENTASI OBJEK 
```
Mata Kuliah Pemrograman Berorientasi Objek (IK290).
Mata Kuliah Wajib Kurikulum (MKWK) Semester Genap.
Fakultas Pendidikan Matematika dan Ilmu Pengetahuan Alam.
Departement Of Computer Science Education. 
Program Studi Ilmu Komputer.

(2658) ROSA ARIANI SUKAMTO, S.T., M.T.
       NIP. 19810918 200912 2 003
       Penata III/c
       Lektor
```
> IBNU ADENG KURNIA - 2101769 - KOM4C2 - © 2023 Univ. Pendidikan Indonesia

## Pert-7. INTRODUCTION TO JAVA GUI: *APACHE NETBEANS- SYNCHRONIZATION*
*Repositori ini dibuat sebagai dokumentasi fortofolio pengerjaan Latihan Praktikum Ke-7 (LP7), kemudian setelah selesai pengerjaan ini mahasiswa diharapkan :*
```
a. Mahasiswa mampu memahami konsep Object Oriented Programming (OOP) digunakan untuk penyelesaian permasalahan-permasalahan yang ada.
b. Mahasiswa mampu memahami perbedaan antara Class dan object, implementasi class dan object, method dalam berbagai bahasa (C++, java, PHP, pyhton) serta type data nya.
c. Kasus-kasus implementasi Graphical User Interface (GUI) dengan menggunakan tools Apache NetBeans. 
d. Mahasiswa mampu memahami konsep Graphical User Interface (GUI) dalam Pemrograman Berorientasi Objek.
e. Mahasiswa mampu memahami konsep Graphical User Interface (GUI) 'Synchronization'.
```

> Saya Ibnu Adeng Kurnia NIM 2101769 mengerjakan Latihan Praktikum 7 (LP7) dalam mata kuliah Desain dan Pemrograman Berorientasi Objek C2 2023
	untuk keberkahan-Nya maka saya tidak melakukan kecurangan seperti yang telah dispesifikasikan. 
	Aamiin.

*Design ini disusun dan/atau digunakan hanya untuk lingkungan sendiri.
	Tidak untuk menjadi konsumsi/kepentingan umum.
	Hanya untuk melengkapi tugas DPBO 2023.*


## Petunjuk Pengerjaan Soal.
Perhatikanlah petunjuk berikut ini dengan seksama :
- Modifikasi kode yang telah diberikan. Ketika ada perintah dari user berupa Klik WASD, skor masih jadi 1 2 3 4 secara hardcode. 
- Kemudian modifikasi pada bagian _skornya_ sehingga _ketika ganti tombol yang diklik, skornya selalu akan terus bertambah._ Sebagai contoh, misalnya :
  - **posisi awal/sekarang adalah 0.** 
  - **Klik W, tambah satu.** _Skor menjadi **1**, berhenti._ ; 
  - **Klik D, tambah satu.** _Skor bertambah lagi menjadi **2**, berhenti._ ; 
  - **Klik lagi (apapun itu selagi pada syantax WASD, tambah satu.** _Maka Skor bertambah satu lagi yakni menjadi **3**._ 
  - Demikian Seterusnya ...
- **Mohon untuk diperhatikan,** jika terjadi error ketika Anda menjalankan kode tersebut, silakan Anda cek pada bagian file **Game.java**, kemudian amati dan periksa pada baris ke-160-an,  yang ditandai dengan kode `bs = createBufferStrategy(SOMEBITS);`  kode pada bagian itu silakan Anda ganti menjadi `SOMEBITS-nya jadi 3 atau 4` untuk meminimalisir kode yang error.
- Masukkan kode yang telah Anda buat pada repository GitHub milik Anda masing-masing dengan nama repository **"LP7C2DPBO2022"** yang diset Public, kemudian kumpulkan tautan/link repository GitHub tersebut [Disini](https://forms.gle/rvb1hKxbQVuYNbhKA) 
- Hanya program pada branch main yang akan diperiksa.
- Jika waktu pengumpulan sudah habis dan Anda ingin mengupdate kode program, update pada branch lain karena mengupdate branch Main setelah waktu pengumpulan berakhir maka program tidak akan diperiksa.
- File README berisi desain program, penjelasan alur, dan dokumentasi saat program dijalankan (screenshot/screen record).
- Anda dapat mengumpulkan hingga batas waktu pengumpulan terakhir yakni pada hari **Minggu, 23 April 2023 M / 02 Syawal 1444 H Pukul 23.59 WIB**.

## Bahasa Pemrograman Yang Dipakai :
- [X] [Java](https://azure.microsoft.com/id-id/resources/cloud-computing-dictionary/what-is-java-programming-language/) : bahasa pemrograman *Object Oriented multiplatform* yang pada umumnya digunakan untuk pengembangan aplikasi dan website yang sampai saat ini dijalankan pada miliaran perangkat di seluruh dunia.


## Tools :
- [X] [JDK](https://www.duniailkom.com/tutorial-belajar-java-part-3-pengertian-jre-dan-jdk/) : JDK atau lengkapnya *Java Development Kit* adalah sebuah paket aplikasi yang berisi JVM *(Java Virtual Machine)* + JRE *(Java Runtime Environment)* + berbagai aplikasi untuk proses pembuatan kode program Java.
- [X] [*Visual Studio Code/Sublime*/Notepad++](https://www.gramedia.com/best-seller/text-editor-terbaik-programmer/) :  sebuah code editor gratis yang bisa dijalankan di perangkat desktop berbasis Windows, Linux, dan MacOS.
- [X] [XAMPP](https://www.jogjahost.co.id/blog/xampp-adalah/) : sebuah software yang menjalankan peran sebagai *local web server/localhost*. XAMPP dikembangkan oleh *Apache Friends*. *Apache Friends* sendiri merupakan proyek nirlaba yang bertujuan untuk mempromosikan server web *Apache*. Selain dari itu terdapat juga di dalamnya MariaDB, PHP, Perl, dan lainnya.
- [X] [*Graphical User Interface* (GUI)](https://bakai.uma.ac.id/2022/09/12/apa-itu-graphical-user-interface-bagaimana-cara-kerjanya/) : *Graphical User Interface* (GUI) adalah komponen sistem visual interaktif untuk aplikasi personal komputer. Menurut **Computer Hope**, GUI menampilkan objek yang mampu memunculkan isu serta merepresentasikan aksi asal pengguna. Menggunakan adanya GUI, kita bisa mengetahui bahwa apa yang kita input telah diterima dan responnya ditampilkan secara visual. GUI dapat terlihat dari perubahan rona, ukuran, visibilitas, serta sejenisnya saat terjadi sebuah hubungan.
- [X] [*Apache NetBeans*](https://netbeans.apache.org/) : Apache NetBeans lebih dari sekadar editor teks. Ini menyoroti kode sumber secara sintaksis dan semantik , memungkinkan Anda dengan mudah memperbaiki kode, dengan berbagai alat praktis dan canggih. Apache NetBeans menyediakan editor, wizard, dan template untuk membantu Anda membuat aplikasi di Java, JavaScript, PHP, HTML5, CSS, dan banyak bahasa lainnya. Apache NetBeans dapat diinstal pada semua sistem operasi yang mendukung Java, yaitu Windows, Linux, Mac OSX dan BSD. Tulis Sekali, Jalankan Di Mana Saja, juga berlaku untuk NetBeans.


## Requirements : 
+ JDK (diharapkan versi yang terbaru)
+ Apache NetBeans (diharapkan versi yang terbaru)
+ Database (PHPMyAdmin) 
+ XAMPP (diharapkan versi yang terbaru)


## Desain Program :
##### ![UML](/tangkapanlayar/UMLTP2.png "1")
Dari bagan diatas, terkait dengan desain yang dibuat, dengan demikian saya uraikan menjadi beberapa point-point penting berikut : 
- `xxx` : 
- `xxx` : 
- `xxx` : 
- `xxx` : 
- `xxx` : 
- `xxx` : 
- `xxx` : 

## Dokumentasi Running Program
### a. Tampilan Awal
### b. Tampilan Setelah Ada nilainya

### **Catatan**
*Jika terjadi hal kesalahan teknis/program error atau lainnya, dengan hormat mohon untuk melakukan validasi kepada saya, karena tentunya hal tersebut dimungkinkan terjadi diluar prakiraan/dugaan. Demikian, harap untuk menjadi maklum. Atas Perhatian dan Kerjasamanya diucapkan terima kasih*

Selamat Menunaikan Ibadah Puasa Ramadan 1444 H / 2023 M bagi Anda yang melaksanakan, semoga Allah Ta'ala memberikan rahmat dan maghfiroh untuk kita semua.
Barakallahu Fiikum.

**Hatur Nuhun.**

**Majalaya, 19 April 2023 M / 28 Ramadan 1444 H.**


#### [Copyright © 2023. IBNU ADENG KURNIA.](https://me-qr.com/id/entry/vcard/MjuIan4)
###### Univ. Pendidikan Indonesia.
###### All Rights Reserved.
