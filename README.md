Siap 👍
Di bawah ini saya kasih **README.md FULL, rapi, dan SIAP COPAS** ke repository GitHub kamu.
Tidak perlu edit apa pun (kecuali nama repo/author kalau mau).

---

````md
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
| HTML5 | Struktur halaman |
| CSS3 | Tampilan antarmuka |
| JavaScript | Interaksi sederhana |
| XAMPP / Laragon | Local server |

---

## 🗂️ Struktur Database

### 📌 Tabel `users`
| Field | Tipe | Keterangan |
|-----|------|------------|
| id | INT | Primary Key |
| nama | VARCHAR(100) | Nama pengguna |
| email | VARCHAR(150) | Email login |
| password | VARCHAR(255) | Password |
| role | ENUM | admin / user |
| created_at | DATETIME | Waktu dibuat |
| deleted_at | DATETIME | Soft delete |

---

### 📌 Tabel `dokter`
| Field | Tipe | Keterangan |
|-----|------|------------|
| id_dokter | INT | Primary Key |
| nama_dokter | VARCHAR(100) | Nama dokter |
| spesialis | VARCHAR(50) | Spesialis |
| hari_praktik | VARCHAR(50) | Hari praktik |
| jam_mulai | TIME | Jam mulai |
| jam_selesai | TIME | Jam selesai |

---

### 📌 Tabel `pasien`
| Field | Tipe | Keterangan |
|-----|------|------------|
| id | INT | Primary Key |
| nama | VARCHAR(100) | Nama pasien |
| deskripsi_keluhan | TEXT | Keluhan |
| id_dokter | INT | Relasi dokter |
| hari_praktik | VARCHAR(50) | Hari praktik |
| jam_mulai | TIME | Jam praktik |
| email | VARCHAR(150) | Email pasien |

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
