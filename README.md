# postest-1-PBO

Nama  : Danial Hirzan Akbary

NIM   : 2409116098

Kelas : Sistem Informasi C.24

## Deskripsi Singkat 

### Manajemen Koleksi Mainan

Program Manajemen Koleksi Mainan adalah aplikasi sederhana berbasis Java yang menerapkan konsep CRUD (Create, Read, Update, Delete) dengan menggunakan ArrayList sebagai media penyimpanan data.

### Fitur utama program ini meliputi:

➕ Menambahkan data mainan baru

📋 Menampilkan daftar semua mainan

✏️ Mengupdate data mainan yang sudah ada

❌ Menghapus data mainan dari koleksi

### Data mainan yang dikelola mencakup:

Nama Mainan

Bahan

Tanggal Produksi

Kondisi

## Output (Alur Program)

### Menu

<img width="458" height="251" alt="image" src="https://github.com/user-attachments/assets/a64bed19-8f6a-43e5-96d3-96acee0ef30d" />

Tampilan awal pada saat kita mnulai running program, disini terdapat menu pilihan CRUD yakni,

1). Tambah Mainan, digunakan untuk menambah koleksi mainan.

2). Lihat Koleksi Mainan, digunakan untuk menampilkan array beruba dafatar mainan yang telah ditambahkan.

3). Ubah Mainan, digunakan untuk mengubah daftar mainan yang telah di buat.

4). Hapus Mainan, digunakan untuk menghapus daftar mainan yang kita inginkan.

5). Keluar, digunakan untuk memberhentikan program.

### Menu Tambah Mainan 

<img width="609" height="179" alt="image" src="https://github.com/user-attachments/assets/cb10926c-c79a-4d5d-b26f-6e919fab999f" />

Di menu ini, program akan meminta pengguna untuk memasukkan data mainan baru. Data yang diminta meliputi:

1). Nama Mainan, nama dari mainan yang ditambahkan.

2). Bahan, bahan dasar pembuatan mainan (misalnya: plastik, kayu).

3). Tanggal Produksi, kapan mainan diproduksi.

4). Kondisi, kondisi mainan saat ini (misalnya: baru, bekas, rusak,).

5). Harga, harga dari mainan tersebut.

Semua input tersebut akan digabung menjadi sebuah array String, lalu disimpan ke dalam ArrayList.
Setelah data berhasil ditambahkan, program menampilkan pesan konfirmasi seperti "Mainan berhasil ditambahkan!".

### Menu Lihat Koleksi Mainan 

<img width="1152" height="74" alt="image" src="https://github.com/user-attachments/assets/7a8e828c-72d6-47c6-bf26-6e86980edbc3" />

Di menu ini, program akan menampilkan seluruh data mainan yang sudah tersimpan di dalam ArrayList.

1). Jika ada data, program akan menampilkan dalam bentuk tabel sederhana dengan urutan:
Nomor, Nama Mainan, Bahan, Tanggal Produksi, Kondisi, Harga

2). Jika belum ada data sama sekali, program akan menampilkan pesan:
"Belum ada mainan yang tersimpan."

Menu ini berguna untuk memantau seluruh koleksi mainan yang sudah ditambahkan oleh pengguna.

### Menu Ubah Mainan

<img width="1153" height="297" alt="image" src="https://github.com/user-attachments/assets/cd938a1f-ce7b-4067-a0ca-8c8d64634268" />

Di menu ini, pengguna dapat mengedit/ mengganti data mainan yang sudah tersimpan di dalam ArrayList.

Program akan menampilkan daftar mainan beserta nomor indeksnya.

Pengguna diminta untuk memilih nomor mainan yang ingin diubah.

Setelah itu, program akan menampilkan data lama dan meminta pengguna untuk memasukkan data baru:Nama Mainan, Bahan, Tanggal, Produksi, Kondisi.

Data lama kemudian digantikan dengan data baru di posisi yang sama.

Jika berhasil, program menampilkan pesan konfirmasi seperti "Data mainan berhasil diperbarui!".

### Menu Hapus Mainan

<img width="1104" height="149" alt="image" src="https://github.com/user-attachments/assets/fe4f82eb-4ed5-4fc0-af8c-e2047eea7c0b" />


Di menu ini, pengguna dapat menghapus data mainan dari daftar koleksi yang tersimpan di dalam ArrayList.

1). Program terlebih dahulu menampilkan daftar mainan dengan nomor indeks.

2). Pengguna diminta memilih nomor mainan yang ingin dihapus.

3). Setelah pilihan dimasukkan, program akan menghapus data mainan tersebut dari ArrayList.

4). Program kemudian menampilkan pesan konfirmasi, misalnya:
"Mainan berhasil dihapus dari daftar!"

5). Jika pengguna memilih nomor yang tidak valid, program akan menampilkan pesan error seperti:
"Nomor mainan tidak ditemukan."

### Menu Keluar

<img width="557" height="297" alt="image" src="https://github.com/user-attachments/assets/23b1c1d5-4d09-4400-869d-ee77f886e927" />


Menu ini digunakan untuk menghentikan jalannya program.

1). Jika pengguna memilih opsi Keluar, perulangan utama (do-while) akan berhenti.

2). Program kemudian menampilkan pesan penutup, misalnya:
"Terima kasih telah menggunakan program Manajemen Koleksi Mainan!"

3). Setelah itu, aplikasi selesai dijalankan.

## Flow Sederhana

Mulai Program

   |
   
   v
   
Tampilkan Menu

   |
   
   v
   
User Pilih Menu

   |
   
   +--> [1] Tambah Mainan --> Input data --> Simpan ke ArrayList
   
   |
   
   +--> [2] Lihat Semua --> Tampilkan isi ArrayList
   
   |
   
   +--> [3] Update --> Pilih index --> Ganti data
   
   |
   
   +--> [4] Hapus --> Pilih index --> Hapus dari ArrayList
   
   |
   
   +--> [5] Keluar --> Selesai
   
   |
   
   v
   
"Ulangi (kecuali pilih 5)

Mulai Program
|
v
Tampilkan Menu
|
v
User Pilih Menu
|
+--> [1] Tambah Mainan --> Input data --> Simpan ke ArrayList
|
+--> [2] Lihat Semua --> Tampilkan isi ArrayList
|
+--> [3] Update --> Pilih index --> Ganti data
|
+--> [4] Hapus --> Pilih index --> Hapus dari ArrayList
|
+--> [5] Keluar --> Selesai
|
v
Ulangi (kecuali pilih 5)"
