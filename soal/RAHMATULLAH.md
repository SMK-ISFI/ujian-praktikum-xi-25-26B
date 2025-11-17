# UJIAN PRAKTIKUM RPL KELAS 11 SEMESTER GANJIL T.A. 2025-2026

Nama: RAHMATULLAH

Kelas: XI RPL

---

## Peraturan

1. Berdoalah sebelum memulai mengerjakan ujian.
2. Bacalah soal dengan cermat dan teliti.
3. Dilarang berdiskusi dengan teman. Pelanggaran akan diberi sanksi.
4. Peserta diberi waktu 10 menit di awal untuk bertanya hal teknis kepada pengawas.

---

# SKENARIO KASUS

Sebuah toko perlengkapan alat tulis bernama **“ATK Maju Bersama”** menjual berbagai barang seperti buku tulis, pulpen, dan penggaris. Selama ini pencatatan stok dilakukan secara manual di buku catatan, sehingga sering terjadi ketidaksesuaian antara barang masuk dan barang keluar.

Pemilik ingin Anda membuat **sistem pencatatan stok barang sederhana** menggunakan **PHP Native + MySQL**, dan tampilan wajib menggunakan **CSS Vanilla atau Tailwind CSS**.

Sistem hanya terdiri dari **satu modul CRUD**, yaitu **data stok barang**.

---

# REQUIREMENT FUNGSIONAL

Anda harus memenuhi requirement berikut:

## MODUL STOK BARANG

**Data yang perlu dicatat:**

- Nama Barang  
- Kategori Barang  
- Jumlah Stok  
- Harga Satuan  
- Tanggal Masuk Barang  

---

# DATABASE

Buat satu tabel dengan struktur:

```
Tabel: stok_barang

id INT AUTO_INCREMENT PRIMARY KEY
nama_barang VARCHAR(100)
kategori VARCHAR(50)
jumlah_stok INT
harga_satuan INT
tanggal_masuk DATE
```


---

# TUGAS PRAKTIKUM

Berikut tugas yang wajib dikerjakan:

---

## 1. Menampilkan Data (READ)

Buat halaman utama untuk menampilkan seluruh data stok barang dalam bentuk tabel.  
Tabel harus berisi:

- Nama Barang  
- Kategori  
- Jumlah Stok  
- Harga Satuan  
- Tanggal Masuk  
- Aksi: **Edit** & **Hapus**

Tampilan wajib menggunakan Tailwind CSS atau CSS Vanilla.

---

## 2. Menambah Data (CREATE)

Buat form untuk menambah data baru dengan field:

- Nama Barang (text)  
- Kategori (text)  
- Jumlah Stok (number)  
- Harga Satuan (number)  
- Tanggal Masuk (date)

Setelah data disimpan, pengguna diarahkan kembali ke halaman utama.

---

## 3. Mengedit Data (UPDATE)

Buat halaman edit untuk mengubah data stok berdasarkan `id`.  
Form harus otomatis menampilkan data lama sebelum diperbarui.

---

## 4. Menghapus Data (DELETE)

Buat fitur untuk menghapus data barang berdasarkan `id`.

---

# STRUKTUR FILE WAJIB

```
/stok_atk
│── koneksi.php
│── index.php → tampil data
│── tambah.php → tambah data
│── edit.php → ubah data
└── hapus.php → hapus data
```