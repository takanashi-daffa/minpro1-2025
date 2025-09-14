# minpro1-2025
*Nama : Daffa Arkhabista,\
nim :2509116018,\
Sistem informasi A*

**Penjelasan code:**\
Baris 1-8: Mendefinisikan data awal. Ada daftar data cuaca yang sudah ditentukan\
Baris 10-11: Meminta pengguna untuk memilih salah satu aksi: create, read, update, atau delete\
Baris 13-25: Bagian create. Mengambil data suhu dan kelembapan baru dari pengguna, menentukan kondisi cuacanya, lalu menambahkannya ke daftar\
Baris 28-36: Bagian read. Meminta pengguna memilih data yang ingin dilihat (1, 2, atau 3), lalu menampilkan data tersebut\
Baris 38-58: Bagian update. Meminta pengguna memilih data yang akan diubah, mengambil data baru, lalu mengganti data lama di daftar\
Baris 61-71: Bagian delete. Meminta pengguna memilih data, lalu menghapusnya dari daftar\
Baris 73-74: Menampilkan semua data cuaca yang ada di akhir program.

Flowchart\
<img width="762" height="1551" alt="minpro1 8 drawio" src="https://github.com/user-attachments/assets/7921730d-78bf-4543-b80a-3279d9a9e2e6" />

**penjelasan program**\
Baris ini mendefinisikan tuple kondisi berisi jenis kondisi cuaca, list informasi_cuaca sebagai data awal cuaca (suhu, kelembapan, kondisi), dan meminta input menu CRUD dari user, lalu mengubahnya menjadi huruf kecil supaya penulisan menu konsisten.\ 

tujuannya .lower agar input menu konsisten, misalnya kalau user ketik CREATE, Create, atau create tetap dianggap sama\
<img width="655" height="249" alt="Screenshot 2025-09-14 033906" src="https://github.com/user-attachments/assets/75ad5e7f-3785-4174-a63d-115d9696ad42" />


Create untuk nambahin data cuaca baru ke list\
Program akan meminta user memasukkan suhu dan kelembapan. Ini adalah dua nilai yang akan menjadi bagian dari data baru\
Setelah memasukkan angka, program akan memeriksa dua angka tersebut dengan serangkaian logika if dan elif untuk menentukan kondisi cuaca (Cerah, Berawan, Hujan, atau Tidak diketahui)\
Data baru yang terdiri dari suhu, kelembapan, dan kondisi cuaca akan digabungkan menjadi sebuah tuple. Lalu, program menggunakan .append() untuk menambahkan tuple ini ke bagian akhir dari list informasi_cuaca\
<img width="691" height="353" alt="Screenshot 2025-09-14 033922" src="https://github.com/user-attachments/assets/a9601824-5243-4b3c-9c15-9003d4ee4c20" />

Read untuk nampilin data yang udah ada\
Fungsi ini memungkinkan user untuk melihat data yang tersimpan. Program akan meminta user untuk memilih data mana yang ingin ditampilkan. Setelah pilihan diberikan, program akan mengakses daftar data dan menyajikan informasi yang dipilih oleh user.\
Program akan meminta user memilih data mana yang ingin dilihat (1, 2, atau 3), 
<img width="1018" height="265" alt="Screenshot 2025-09-14 033947" src="https://github.com/user-attachments/assets/99b9f022-4284-483d-a88f-27ec72f6781c" />

Update untuk ngubah data jadi data baru\
digunakan untuk memodifikasi data yang sudah ada. Pertama, user akan diberikan pilihan data mana yang akan diperbarui. Lalu, setelah user memilih, program akan meminta masukan suhu dan kelembapan yang baru. Dengan data baru tersebut, maka data lama akan di-update di dalam daftar.\
<img width="1038" height="522" alt="Screenshot 2025-09-14 033957" src="https://github.com/user-attachments/assets/517c6900-0a1a-4baf-9b6d-99fd9a8aaf89" />

Delete untuk ngapus data dari list\
Fungsi ini memungkinkan user untuk menghapus data yang tidak lagi diperlukan. Program akan meminta user untuk memilih data yang ingin dihapus, lalu data tersebut akan dikeluarkan dari daftar\
<img width="996" height="284" alt="Screenshot 2025-09-14 034007" src="https://github.com/user-attachments/assets/fc907a28-76fd-43ad-a02c-e08d9f833d79" />

**hasil dari coding saya**\
<img width="1052" height="892" alt="Screenshot 2025-09-14 033838" src="https://github.com/user-attachments/assets/6eec8420-c6a3-49f6-ab8f-0738f7acbd28" />\
<img width="1124" height="911" alt="Screenshot 2025-09-14 033855" src="https://github.com/user-attachments/assets/529c4c49-a72f-406f-bb3b-820e88fefd2b" />\
<img width="997" height="1008" alt="Screenshot 2025-09-14 034332" src="https://github.com/user-attachments/assets/6808774c-2498-4146-9cc1-1550a2320129" />\
<img width="816" height="176" alt="Screenshot 2025-09-14 034347" src="https://github.com/user-attachments/assets/e82469cd-9ec6-474a-a7fa-57346c3162d5" />



