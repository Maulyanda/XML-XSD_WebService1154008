# XML dan XSD

Maulyanda_1154008

Assalamualaikum wr.wb

Pada tugas praktikum kali ini terdapat 2 file yg harus dibuat yaitu file XML dan XSD dan juga membuat pola untuk email contoh : abc@xyz.com

Pengertian XML 
  XML (eXtensible Markup Language) digunakan dalam banyak aspek pengembangan web, sering dipakai untuk menyederhanakan penyimpanan dan pertukaran data.

File XML biasa digunakan untuk membuat struktur-struktur atau elemen-elemen dari satu atau beberapa data, sedangkan file XSD biasa digunakan untuk mengecek apakah file XML yang dibuat well from atau tidak.

Langkah-langkah dalam membuat File XML dan XSD :

1. Buatlah project baru pada menu File->New->Project->Plug-in Development->Plug-in Project, lalu buat nama sesuai project yang mau dibuat, Contoh : TugasPrak2
2. pada Project yang sudah dibuat,klik kanan pada package lalu pilih other->XML->XML File, Beri Nama file XML nya Mahasiswa.xml, Lalu Finish.
3. Isi Source pada File XML
4. Setelah selesai membuat File XML, klik kanan pada File Mahasiswa.xml->Create XML Definition->pilih XML Schema->Beri Nama File Contoh Mahasiswa.xsd->Finish
5. Selanjutnya Menyambungkan XML File dan XSD File, dengan cara klik kanan pada File Mahasiswa.xsd->Generate->XML File->Beri nama file Contoh : Proyek.xml ->Finish
6. Copy (xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xsi:noNamespaceSchemaLocation="Mahasiswa.xsd") pada file proyek.xml ke file Mahasiswa.xml pada element utama, lalu save.
7. Setelah validasi bisa dilakukan, selanjutnya kita membuat pada element email pada file Mahasiwa.xml menggunakan tanda @ dan.
8. Klik pada file Mahasiswa.xsd, pilih element/struktur email di mahasiswa.xsd, pilih constraint dan pattern, add tanda (@) dan (.). agar tanda tersebut harus ada pada element/struktur email.
9. Cek Validasi pada Mahsiswa.xml, jika pada element email tidak menggunakan tanda (@) atau (.), ketika di validasi eror berati cara pada NO.8 telah berhasil diterapkan.
10. Selesai

Demikian langkah-langkah dalam membuat File XML dan XSD, dan juga cara menerapkan tanda (@) dan (.) pada element email.

Terimakasih, Semoga Bermanfaat.

Wassalmualaikum wr.wb
