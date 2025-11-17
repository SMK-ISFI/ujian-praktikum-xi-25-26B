# UJIAN PRAKTIKUM RPL KELAS 11 SEMESTER GANJIL  
T.A. 2025-2026

Nama: RAFI HAFIDZ WAHYUDI

Kelas: XI RPL

---

**Peraturan:**

1. Berdoalah sebelum memulai mengerjakan ujian.  
2. Bacalah soal dengan cermat dan teliti.  
3. Dilarang berdiskusi selama ujian, apabila melanggar akan mendapatkan sanksi.  
4. Peserta ujian diberikan waktu 10 menit diawal untuk menanyakan hal yang belum dipahami kepada pengawas.

---

### **Skenario**

Unit **“Kantin Sehat Sekolah (KSS)”** ingin membuat sistem digital untuk mengelola **data menu makanan** yang dijual setiap hari. Selama ini petugas menulis daftar menu secara manual di papan tulis, sehingga sering terjadi kesalahan informasi, seperti harga tidak sesuai atau menu tidak diperbarui.

Anda diminta membuat aplikasi web sederhana untuk mengelola **menu kantin sekolah**.  
Aplikasi hanya diakses oleh petugas kantin, sehingga harus memiliki **halaman login** sebelum masuk ke halaman pengelolaan data.

---

### **A. Ketentuan Login**

Buat halaman **index.php** dengan:

- Input **username**
- Input **password**
- Tombol **Login**

Validasi login menggunakan **IF–ELSE (tanpa database)**.

Akun login yang benar:

**Username:** petugaskantin  
**Password:** kss2025  

Jika username dan password benar → redirect ke halaman CRUD (beranda.php)  
Jika salah → tampilkan pesan **“Username atau Password salah!”**

---

### **B. CRUD Data Menu Kantin**

Anda harus membuat satu modul CRUD untuk **Data Menu Makanan**.

**Struktur tabel (wajib):**  
Nama tabel: **menu**

| Nama Kolom | Tipe                 | Keterangan    |
|------------|----------------------|----------------|
| id         | INT AUTO_INCREMENT   | PRIMARY KEY    |
| nama_menu  | VARCHAR(100)         |                |
| kategori   | VARCHAR(50)          |                |
| harga      | INT                  |                |
| tersedia   | VARCHAR(10)          | Ya/Tidak       |

---

### **C. Fungsi CRUD yang Harus Ada**

1. **Create – tambah.php**  
   - Form input: nama_menu, kategori, harga, tersedia  
   - Data tersimpan ke database  

2. **Read – beranda.php**  
   - Menampilkan seluruh data menu  
   - Tampilkan kolom: No, Nama Menu, Kategori, Harga, Tersedia, Aksi  
   - Aksi berupa tombol **Edit** dan **Hapus**

3. **Update – edit.php**  
   - Menampilkan form edit  
   - Data hasil edit disimpan ke database  

4. **Delete – hapus.php**  
   - Menghapus data berdasarkan ID  

---

### **D. Ketentuan File yang Wajib Dibuat**

1. index.php (halaman login)  
2. beranda.php (halaman daftar menu)  
3. tambah.php  
4. edit.php  
5. hapus.php  
6. koneksi.php  

---
