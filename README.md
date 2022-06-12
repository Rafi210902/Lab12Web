                                                                      LAPORAN PRAKTIKUM 12
                                                                    FRAMEWORK LANJUTAN (CRUD)
                                                                        PEMROGRAMAN WEB
Nama		: Rafi Hanif R.
NIM		: 312010358
Kelas		: TI.20.A.2
Mata Kuliah	: Pemrograman Web

PENDAHULUAN 
Segala Puji bagi Tuhan Semesta Alam yang telah memberikan kita berbagai macam ni’mat yaitu Ni’mat Islam, Ni’mat Iman serta Ni’mat Sehat Wal Afiat sehingga saya dapat menyusun Laporan Praktikum 12 ini dengan baik dan benar. 
Laporan Praktikum ini saya buat bertujuan untuk mengumpulkan Tugas Pertemuan 12 yang telah diberikan oleh Dosen Pengampu yaitu Bapak Agung Nugroho yang telah memberikan Materi dan Instruksi Praktikum kepada Mahasiswa/I. 

TUJUAN 
1.	Mahasiswa mampu memahami konsep dasar Model
2.	Mahasiswa mampu memahami konsep dasar CRUD 
3.	Mahasaswa mampu membuat program sederhana menggunakan Framework Codeigniter 4

LANDASAN TEORI
Pembuatan Laporan Praktikum 12 ini dibuat berdasarkan cara-cara dari Instruksi yang telah diberikan oleh Dosen Pengampu yaitu Bapak Agung Nugroho. Dan disini Mahasiswa/I diajarkan untuk memahami bagaimana cara-cara membuat CRUD Framework Lanjutan dengan Instruksi yang tersedia agar bisa dipahami oleh Mahasiswa/I, agar para Mahasiswa/I dapat mempraktikkannya dengan mudah.
Selain itu, pembuatan Laporan Praktikum 12 ini, bertujuan untuk melatih Mahasiswa/I dalam membuat Laporan dengan bahasa yang baku dan benar. Dan juga untuk melatih membuat Skripsi yang baik dan benar supaya tidak ada kesalahan penulisan kata-kata.

BAHAN-BAHAN
-	Visual Studio Code
-	Xampp (dengan mengaktifkan Apache dan MySQL)
-	Google Chrome

CARA-CARA
1.	Pertama-tama kita aktifkan Apache dan MySQL pada Xampp Control Panel seperti dibawah berikut.
 ![image](https://user-images.githubusercontent.com/102600434/173242710-eaa8f986-fa4c-4c82-afcf-e99749d8b6a5.png)


2.	Kemudian buka browser dan ketik http://localhost/phpmyadmin kemudian klik New -> lalu klik SQL pada baris ketiga sebelah atas dari kiri setelah Browse lalu ketik kata untuk membuat databasenya -> klik Go pada sebelah kanan bawah jika sudah selesai membuat database tersebut seperti dibawah ini.
![image](https://user-images.githubusercontent.com/102600434/173242856-22bec03c-9667-4909-8fba-fa01de0035d8.png)

![image](https://user-images.githubusercontent.com/102600434/173242860-556246f3-fbfb-4cbf-a772-d6aa98ab45f3.png)
 

3.	Lalu klik SQL pada baris kedua sebelah atas dari kiri setelah Structure lalu ketik seperti dibawah ini -> klik Go pada sebelah kanan bawah jika sudah selesai .
![image](https://user-images.githubusercontent.com/102600434/173242871-1a16dbf1-1d4d-4273-8b42-f542eaf99515.png)

![image](https://user-images.githubusercontent.com/102600434/173242879-b0f28c71-6b35-42f8-9093-9c0ed06b9632.png)


4.	Selanjutnya kita melakukan konfigurasi databasenya dengan membuka notepad .env dengan mengklik Xampp -> htdocs -> lab11_ci -> ci4 lalu klik dua kali pada notepad .env dan kita melakukan konfigurasi sebagai berikut (untuk password yang sebelumnya bertuliskan “root” sebaiknya dihapus atau dikosongkan saja seperti dibawah ini).
![image](https://user-images.githubusercontent.com/102600434/173242894-bd10d8de-132f-411c-b160-797f8d95413d.png)

![image](https://user-images.githubusercontent.com/102600434/173242898-55056078-578a-484e-8e4b-b9f1f579d1d6.png)

![image](https://user-images.githubusercontent.com/102600434/173242905-3779122a-e853-4499-ad4d-b16d07827136.png)

![image](https://user-images.githubusercontent.com/102600434/173242912-ec32a544-a92a-4d22-9d91-0540f9069cb1.png)

![image](https://user-images.githubusercontent.com/102600434/173242929-59a7095b-07a7-4eb4-9928-3bb8abf78443.png)

![image](https://user-images.githubusercontent.com/102600434/173242935-49cf935b-5899-4f6a-bff4-5fa78fca911f.png)
 

5.	Kemudian langkah selanjutnya adalah membuat model untuk memproses data Artikel. Disini saya membuat file baru dengan nama ArtikelModel.php didalam folder lab11_ci/ci4/app/Models seperti dibawah berikut.
 ![image](https://user-images.githubusercontent.com/102600434/173242943-8d45fa0d-e931-4bbf-853e-5ae736b95e39.png)

![image](https://user-images.githubusercontent.com/102600434/173242949-ee2ebf59-020e-4b86-b65a-c7ba2f48560d.png)

![image](https://user-images.githubusercontent.com/102600434/173242955-0cfdc137-a3e5-4d72-9448-52e4c27ebaf5.png)

![image](https://user-images.githubusercontent.com/102600434/173242958-1cf822a6-7f75-41c0-959f-3ff5e23d032a.png)

![image](https://user-images.githubusercontent.com/102600434/173242962-def828c3-a576-4c79-96bc-865e24643eb1.png)
 

Setelah itu tekan shortcut CTRL+S untuk menyimpan file ArtikelModel.php.

6.	Untuk membuat controller saya membuat file baru dengan nama Artikel.php pada folder lab11_ci/ci4/app/Controllers seperti dibawah ini.
![image](https://user-images.githubusercontent.com/102600434/173242984-249b65f2-ba1c-4014-af8d-4f493ab029a2.png)

![image](https://user-images.githubusercontent.com/102600434/173242988-1384e80f-54a3-4da3-8a4f-a74918670475.png)

![image](https://user-images.githubusercontent.com/102600434/173242996-42c25832-e4c8-4dad-87de-f3842d264a05.png)

![image](https://user-images.githubusercontent.com/102600434/173243003-3f133941-2a0c-4b4c-9a57-d0e80ba3a91f.png)

![image](https://user-images.githubusercontent.com/102600434/173243009-aadee11a-cadb-408a-9fd1-88aacb2f3eb3.png)

Setelah itu tekan shortcut CTRL+S untuk menyimpan file Artikel.php.

7.	Selanjutnya saya membuat file baru dengan nama index.php pada folder lab11_ci/ci4/app/views seperti dibawah ini.
 ![image](https://user-images.githubusercontent.com/102600434/173243026-e8cea472-1d0e-4b00-be15-3f67441805b8.png)

![image](https://user-images.githubusercontent.com/102600434/173243030-8ad0dd93-c77c-4ad7-be3a-f375ca581aae.png)

![image](https://user-images.githubusercontent.com/102600434/173243035-b11ed424-6aad-46ca-bd0b-34b0541391bb.png)

![image](https://user-images.githubusercontent.com/102600434/173243040-97b70491-1edf-4d6d-99ea-cbbf15812936.png)

![image](https://user-images.githubusercontent.com/102600434/173243043-2bde522c-b613-40b8-84db-860f88414903.png)

Setelah itu tekan shortcut CTRL+S untuk menyimpan file index.php.

8.	

KESIMPULAN 	
	Dari cara-cara pembuatan Framework Lanjutan dari CRUD ini, Mahasiswa/I bisa dapat mempraktikkan secara benar dan tepat. Sesuai dengan Instruksi Praktikum yang telah diberikan kita dapat mengambil pelajaran dari Praktikum ini supaya kita dilatih dalam membuat Framework CRUD agar menjadi suatu ilmu yang sangat bermanfaat bagi para Mahasiwa/i. 
