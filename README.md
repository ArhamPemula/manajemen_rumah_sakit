# 🏥 Manajemen Rumah Sakit

Project ini merupakan **aplikasi web CRUD Manajemen Rumah Sakit** yang dibuat menggunakan **PHP (Native)** dan **MySQL**.  
Aplikasi ini bertujuan untuk membantu pengelolaan data pasien, dokter, serta jadwal praktik secara terkomputerisasi.

Aplikasi dijalankan pada **local server** seperti **XAMPP** atau **Laragon**.

---

## ✨ Fitur Aplikasi

### 🧑‍⚕️ Manajemen Pasien
- Menampilkan data pasien
- Menambahkan data pasien baru
- Mengubah data pasien
- Menghapus data pasien

### 🩺 Manajemen Dokter
- Menampilkan daftar dokter
- Menampilkan spesialis dokter
- Menampilkan jadwal praktik dokter

### 🔐 Autentikasi
- Login Admin
- Sistem session untuk keamanan dashboard

---

## 💻 Teknologi yang Digunakan

| Teknologi | Keterangan |
|---------|-----------|
| PHP (Native) | Backend logic |
| MySQL | Database |
| HTML | Struktur halaman |
| CSS | Tampilan antarmuka |
| JavaScript | Interaksi sederhana |
| XAMPP / Laragon | Local server |

---

## 🗂️ Struktur Database

### 📌 Tabel `users`
| Field | Tipe | Keterangan |
|-----|------|------------|
| id | INT | Primary Key |
| nama | VARCHAR | Nama pengguna |
| email | VARCHAR | Email login |
| password | VARCHAR | Password |

---

### 📌 Tabel `dokter`
| Field | Tipe | Keterangan |
|-----|------|------------|
| id_dokter | INT | Primary Key |
| nama_dokter | VARCHAR | Nama dokter |
| spesialis | VARCHAR | Spesialis |
| hari_praktik | VARCHAR | Hari praktik |
| jam_mulai | TIME | Jam mulai |
| jam_selesai | TIME | Jam selesai |

---

### 📌 Tabel `pasien`
| Field | Tipe | Keterangan |
|-----|------|------------|
| id | INT | Primary Key |
| nama | VARCHAR | Nama pasien |
| deskripsi_keluhan | TEXT | Keluhan |
| id_dokter | INT | Relasi dokter |
| hari_praktik | VARCHAR | Hari praktik |
| jam_mulai | TIME | Jam praktik |
| email | VARCHAR | Email pasien |

---

## 🚀 Cara Menjalankan Project

### 1️⃣ Clone Repository
```bash
git clone https://github.com/username/manajemen_rumah_sakit.git
````

### 2️⃣ Pindahkan ke Folder Server

* **XAMPP** → `htdocs/`
* **Laragon** → `www/`

### 3️⃣ Buat Database

1. Buka `phpMyAdmin`
2. Buat database dengan nama:

   ```sql
   db_rumah_sakit
   ```
3. Import file SQL yang tersedia di project

---

### 4️⃣ Konfigurasi Koneksi Database

Edit file:

```
config/config.php
```

```
$db   = "db_rumah_sakit";
```

---

### 5️⃣ Jalankan di Browser

```
http://localhost/manajemen_rumah_sakit
```




tinggal bilang saja 👍
```
