# UJIAN PRAKTIKUM RPL KELAS 11 SEMESTER GANJIL  
T.A. 2025-2026

Nama: MUHAMMAD RASYID RIDHO

Kelas: XI RPL

---

**Peraturan:**

1. Berdoalah sebelum memulai mengerjakan ujian.  
2. Bacalah soal dengan cermat dan teliti.  
3. Dilarang berdiskusi selama ujian, apabila melanggar akan mendapatkan sanksi.  
4. Peserta ujian diberikan waktu 10 menit diawal untuk menanyakan hal yang belum dipahami kepada pengawas.

---

### **Skenario**

Sebuah unit **“Pusat Kegiatan Siswa (PKS)”** sedang membangun sistem digital untuk mengelola **pendaftaran kegiatan ekstrakurikuler**. Selama ini proses pendaftaran dilakukan melalui formulir kertas sehingga sering terjadi penumpukan dan hilangnya data. Anda diminta membuat aplikasi web sederhana untuk mengelola **data pendaftar ekstrakurikuler**.  

Aplikasi hanya digunakan oleh pengurus internal, sehingga harus memiliki **halaman login sederhana** sebelum masuk ke halaman pengelolaan data.

---

### **A. Ketentuan Login**

Buat halaman **index.php** dengan:

- Input **username**
- Input **password**
- Tombol **Login**

Validasi login menggunakan **IF–ELSE (tanpa database)**.

Akun login yang benar:

**Username:** adminpks  
**Password:** ekskul2025  

Jika username dan password benar → redirect ke halaman CRUD (beranda.php)  
Jika salah → tampilkan pesan **“Username atau Password salah!”**

---

### **B. CRUD Data Pendaftar Ekstrakurikuler**

Anda harus membuat satu modul CRUD untuk **Data Pendaftar Ekstrakurikuler**.

**Struktur tabel (wajib):**  
Nama tabel: **pendaftar**

| Nama Kolom | Tipe                 | Keterangan    |
|------------|----------------------|----------------|
| id         | INT AUTO_INCREMENT   | PRIMARY KEY    |
| nama       | VARCHAR(100)         |                |
| kelas      | VARCHAR(10)          |                |
| ekskul     | VARCHAR(50)          |                |
| no_hp      | VARCHAR(15)          |                |

---

### **C. Fungsi CRUD yang Harus Ada**

1. **Create – tambah.php**
   - Form input: nama, kelas, ekskul, no_hp  
   - Data tersimpan ke database

2. **Read – beranda.php**
   - Menampilkan seluruh data pendaftar  
   - Tampilkan kolom: No, Nama, Kelas, Ekstrakurikuler, No HP, Aksi  
   - Aksi berupa tombol **Edit** dan **Hapus**

3. **Update – edit.php**
   - Menampilkan form edit  
   - Data hasil edit disimpan ke database

4. **Delete – hapus.php**
   - Menghapus data berdasarkan ID

---

### **D. Ketentuan File yang Wajib Dibuat**

1. index.php (halaman login)  
2. beranda.php (halaman daftar data pendaftar)  
3. tambah.php  
4. edit.php  
5. hapus.php  
6. koneksi.php  

---
