# UJIAN PRAKTIKUM RPL KELAS 11 SEMESTER GANJIL T.A. 2025-2026

Nama: M FITRI FAHREZI

Kelas: XI RPL

---

## Peraturan

1. Berdoalah sebelum memulai mengerjakan ujian.  
2. Bacalah soal dengan cermat dan teliti.  
3. Dilarang berdiskusi selama ujian, apabila melanggar akan mendapatkan sanksi.  
4. Peserta ujian diberikan waktu 10 menit diawal untuk menanyakan hal yang belum dipahami kepada pengawas.  

---

# Skenario

Sebuah **Toko Buku Online** bernama *BukuKita* ingin membuat sistem pendataan buku sederhana untuk menggantikan pencatatan manual mereka. Pemilik toko meminta Anda sebagai developer junior untuk membuat **sistem manajemen data buku**.

Sistem ini harus dapat mencatat daftar buku yang tersedia, termasuk **judul buku, penulis, harga, dan kategori** (misalnya: Fiksi, Non-Fiksi, Pendidikan, Novel, dll).

Anda diminta membuat aplikasi **CRUD (Create, Read, Update, Delete)** sederhana menggunakan **PHP Native** dan **MySQL**, serta wajib menggunakan **CSS Vanilla atau Tailwind CSS** untuk tampilan antarmuka.

---

# A. Instruksi Praktikum

Buatlah aplikasi web dengan ketentuan berikut:

### 1. Halaman Read (Daftar Buku)
- Menampilkan seluruh data buku dari database dalam bentuk tabel.
- Setiap baris harus memiliki tombol **Edit** dan **Hapus**.
- Wajib diberikan styling menggunakan **Tailwind CSS atau CSS Vanilla**.

### 2. Halaman Create (Tambah Buku)
- Menyediakan form untuk menambah data buku.
- Setelah submit, data harus masuk ke database dan kembali ke halaman daftar buku.

### 3. Halaman Update (Edit Buku)
- Menampilkan data buku berdasarkan ID.
- Form harus bisa mengubah data buku yang sudah ada.
- Setelah edit, kembali ke halaman daftar buku.

### 4. Fitur Delete
- Menghapus data buku berdasarkan ID.



# B. Ketentuan Database
```
Tabel: buku

id INT AUTO_INCREMENT PRIMARY KEY
judul VARCHAR(150)
penulis VARCHAR(100)
harga INT
kategori VARCHAR(50)
```


# C. Ketentuan File yang Wajib Dibuat

1. index.php  
2. tambah_buku.php  
3. edit_buku.php  
4. hapus_buku.php  
5. koneksi.php  


