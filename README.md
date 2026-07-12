# VA-Fashion-Samarinda-App

Nama:Anindita Amelia
NIM :BD2303001

Studi Kasus Apliikasi
Pengembangan Aplikasi Mobile VA Fashion Samarinda Berbasis Flutter untuk Mendukung Penjualan Fashion Wanita Secara Digital

Deskripsi Aplikasi
VA Fashion Samarinda adalah aplikasi mobile berbasis Flutter yang dirancang untuk memudahkan pelanggan melihat katalog produk fashion wanita secara terstruktur dan membantu pemilik toko mengelola data produk melalui fitur CRUD lengkap, serta meningkatkan efisiensi penjualan melalui platform mobile.

Tujuan Aplikasi
- Mempermudah proses pembelian produk fashion wanita
- Menyediakan tampilan katalog yang menarik dan mudah digunakan
- Mendukung digitalisasi bisnis fashion lokal
- Memberikan pengalaman belanja online yang praktis
- Menghubungkan pelanggan dengan toko via WhatsApp

Fitur Utama
      Fitur	                          Keterangan
🌸 Splash Screen	   Animasi gradient pink elegan saat pertama buka
📖 Onboarding        3 slide pengenalan aplikasi (hanya muncul pertama kali)
🔐 Login             Autentikasi dengan validasi form
🏠 Home	             Banner, kategori, promo, dan produk terbaru
🛍️ Katalog Produk	   Tab kategori: Dress, Hijab, Tas, Sepatu, Aksesoris
🔍 Search	           Cari produk berdasarkan nama atau kategori
❤️ Favorit	         Simpan produk favorit
📦 Detail Produk	   Info lengkap: foto, harga, stok, deskripsi
➕ CRUD Produk	     Tambah, Edit, Hapus produk dengan foto
💬 WhatsApp CTA	     Tombol langsung chat ke nomor toko
👤 Profil Toko	     Informasi lengkap toko dan logout

🎨Identitas Visual
Warna Utama   : #FF69B4 (Hot Pink)
Baby Pink     : #FFD1DC
Putih         : #FFFFFF
Abu Soft      : #F5F5F5
Teks Gelap    : #333333

🗂️ Struktur Folder
lib/
├── main.dart                    # Entry point aplikasi
├── models/
│   └── product.dart             # Model produk (Isar)
├── utils/
│   ├── app_theme.dart           # Tema & warna aplikasi
│   └── database_service.dart    # Layanan database Isar
├── widgets/
│   └── product_card.dart        # Widget kartu produk
└── screens/
    ├── splash_screen.dart        # Halaman splash
    ├── onboarding_screen.dart    # Halaman onboarding
    ├── login_screen.dart         # Halaman login
    ├── main_screen.dart # Bottom navigation utama 
    ├── home_screen.dart # Halaman beranda 
    ├── produk_screen.dart # Katalog produk 
    ├── detail_screen.dart # Detail produk 
    ├── crud_screen.dart # Kelola produk 
    ├── tambah_produk_screen.dart # Tambah produk 
    ├── edit_produk_screen.dart # Edit produk 
    └── profil_screen.dart # Profil toko 
    assets/ 
    └── images/ 
    └── banner.png # Banner VA Fashion

Cara Menjalankan Aplikasi
Flutter SDK 3.19+
Android Studio / VS Code
Android Emulator atau device fisik
Langkah Instalasi

1. Clone repository
git clone https://github.com/username/va_fashion_samarinda.git
cd va_fashion_samarinda

2. Install dependencies
flutter pub get

3. Generate Isar database
dart run build_runner build --delete-conflicting-outputs

4. Jalankan aplikasi
flutter run

Akun Demo
Role	      Email	              Password
Admin	  admin@vafashion.com	  vafashion123
User	  user@vafashion.com	  user123

Alur Aplikasi
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

📸 Screenshot Aplikasi
1. Onboarding




2. Home




3. CRUD Produk



📞 Kontak Toko
WhatsApp : 0853-4506-5361
Instagram : @vafashion.samarinda
Lokasi : Samarinda, Kalimantan Timur

🔗 Repository GitHub

 
