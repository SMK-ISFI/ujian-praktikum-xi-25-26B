# UJIAN PRAKTIKUM RPL KELAS 11 SEMESTER GANJIL T.A. 2025-2026

Nama: RENY AULIA PUTRI

Kelas: XI RPL

---

**Peraturan:**

1. Berdoalah sebelum memulai mengerjakan ujian.
2. Bacalah soal dengan cermat dan teliti.
3. Dilarang berdiskusi selama ujian, apabila melanggar akan mendapatkan sanksi.
4. Peserta ujian diberikan waktu 10 menit diawal untuk menanyakan hal yang belum dipahami kepada pengawas.

### **LATAR BELAKANG**

Sebuah restoran bernama **Resto Makan Lezat** menerima banyak tamu setiap hari. Admin masih mencatat reservasi meja menggunakan buku, sehingga sering terjadi kesalahan pencatatan, nomor meja ganda, atau tamu tidak terdata.

Pemilik meminta Anda membuat aplikasi **pendataan reservasi meja restoran** sederhana menggunakan **PHP Native, MySQL, TailwindCSS atau CSS Vanilla**.

Aplikasi ini terdiri dari **1 modul CRUD**, yaitu **CRUD Data Reservasi Meja**.

### **TUJUAN PEMBUATAN SISTEM**

Anda diminta membuat sistem yang dapat:

1. Mencatat pelanggan yang melakukan reservasi meja  
2. Menampilkan daftar reservasi  
3. Mengedit data reservasi  
4. Menghapus data reservasi  

### **KOMPONEN SOAL**

#### **Halaman Daftar Reservasi (READ)**

Tampilkan data dari database dalam bentuk tabel dengan kolom:

- Nama Pelanggan  
- Nomor Telepon  
- Jumlah Orang  
- Waktu Reservasi  
- Nomor Meja (1–20)  
- Tombol Edit  
- Tombol Hapus  

Tabel harus memiliki styling menggunakan Tailwind atau CSS buatan sendiri.

#### **Halaman Tambah Data Reservasi (CREATE)**

Buat form yang berisi:

- Nama Pelanggan (text)  
- Nomor Telepon (text/number)  
- Jumlah Orang (number)  
- Waktu Reservasi (datetime-local)  
- Pilih Nomor Meja (select → 1 sampai 20)  

Saat disubmit:

- Data disimpan ke database  
- Arahkan kembali ke halaman daftar reservasi  


#### **Halaman Edit Reservasi (UPDATE)**

- Data harus otomatis terisi sesuai ID yang dipilih  
- Setelah disimpan → kembali ke halaman daftar  



#### **Hapus Reservasi (DELETE)**

- Hapus data berdasarkan ID  



### **STRUKTUR DATABASE**

```
Tabel: reservasi

id INT PRIMARY KEY AUTO_INCREMENT
nama_pelanggan VARCHAR(100)
telepon VARCHAR(20)
jumlah_orang INT
waktu DATETIME
nomor_meja INT
```

### **STRUKTUR FILE**

```
/resto_app
│── koneksi.php
│── index.php → daftar reservasi
│── tambah.php → tambah data
│── edit.php → ubah data
└── hapus.php → hapus data
```

