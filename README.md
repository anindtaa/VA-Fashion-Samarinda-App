# 👗 VA Fashion Samarinda


* **Nama :** Anindita Amelia
* **NIM  :**BD2303001

---

## 🧾 Deskripsi Aplikasi

VA Fashion Samarinda adalah aplikasi mobile berbasis Flutter yang dirancang untuk memudahkan pelanggan melihat katalog produk fashion wanita secara terstruktur dan membantu pemilik toko mengelola data produk melalui fitur CRUD lengkap.
Aplikasi ini dibuat sebagai solusi digital untuk mendukung bisnis fashion lokal di Samarinda agar lebih berkembang melalui platform online.

---

## 🎯 Tujuan Aplikasi

* Mempermudah proses pembelian produk fashion wanita
* Menyediakan tampilan katalog yang menarik dan mudah digunakan
* Mendukung digitalisasi bisnis fashion lokal
* Memberikan pengalaman belanja online yang praktis
* Menghubungkan pelanggan dengan toko via WhatsApp

---

## ⚙️ Fitur Utama Aplikasi
🌸 Splash Screen	Animasi gradient pink elegan saat pertama buka
📖 Onboarding	3 slide pengenalan aplikasi (hanya muncul pertama kali)
🔐 Login	Autentikasi dengan validasi form
🏠 Home	Banner, kategori, promo, dan produk terbaru
🛍️ Katalog Produk	Tab kategori: Dress, Hijab, Tas, Sepatu, Aksesoris
🔍 Search	Cari produk berdasarkan nama atau kategori
❤️ Favorit	Simpan produk favorit
📦 Detail Produk	Info lengkap: foto, harga, stok, deskripsi
➕ CRUD Produk	Tambah, Edit, Hapus produk dengan foto
💬 WhatsApp CTA	Tombol langsung chat ke nomor toko
👤 Profil Toko	Informasi lengkap toko dan logout

🎨 Identitas Visual
Warna Utama   : #FF69B4 (Hot Pink)
Baby Pink     : #FFD1DC
Putih         : #FFFFFF
Abu Soft      : #F5F5F5
Teks Gelap    : #333333

🗺️ Alur Aplikasi
Splash Screen
      ↓
 Onboarding
      ↓
    Login
      ↓
    Home
  ┌───┼───────────┐
  ↓   ↓           ↓
Produk  CRUD    Profil
  ↓      ├── Tambah
Detail   ├── Edit
         └── Hapus

## 🔄 Alur Penggunaan Aplikasi

1. Pengguna membuka aplikasi
2. Masuk ke halaman onboarding
3. Masuk ke halaman utama (home)
4. Melihat daftar produk fashion
5. Pengguna dapat:
   * Menambahkan produk
   * Mengedit produk
   * Menghapus produk
6. Pengguna dapat melihat detail produk yang dipilih

## 📸 Screenshot Aplikasi

### 1. Onboarding Screen

https://github.com/anindtaa/VA-Fashion-Samarinda-App/blob/main/splash%20screen.jpeg

### 2. Home Screen

https://github.com/anindtaa/VA-Fashion-Samarinda-App/blob/main/home%20page.jpeg

### 3. CRUD Feature

https://github.com/anindtaa/VA-Fashion-Samarinda-App/blob/main/crud%20produk.png

---

## 🛠️ Teknologi yang Digunakan

* Flutter (Framework)
* Dart (Bahasa Pemrograman)
* Android Studio / VS Code
* GitHub (Version Control)

---

## 📂 Struktur Project

```
lib/
 ┣ models/
 ┣ screens/
 ┣ widgets/
 ┣ services/
 ┗ main.dart
```

---

Fitur CRUD Produk
Field	Tipe	Keterangan
id	Id	Auto increment
namaProduk	String	Nama produk
kategori	String	Dress/Hijab/Tas/Sepatu/Aksesoris
harga	double	Harga produk
stok	int	Jumlah stok
deskripsi	String	Deskripsi produk
gambar	String?	Path foto produk
isFavorit	bool	Status favorit

📞 Kontak Toko
WhatsApp : 0853-4506-5361
Instagram : @vafashion.samarinda
Lokasi : Samarinda, Kalimantan Timur

## Penutup

Aplikasi ini diharapkan dapat membantu perkembangan bisnis fashion lokal serta memberikan pengalaman belanja online yang mudah dan menyenangkan bagi pengguna.

Terima kasih 🙏
