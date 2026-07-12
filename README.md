# 📱 VA Fashion Samarinda — Panduan Setup Flutter

## Struktur File yang Dibuat

```
va_fashion/
├── pubspec.yaml
└── lib/
    ├── main.dart
    ├── models/
    │   └── product.dart
    ├── utils/
    │   ├── app_theme.dart
    │   └── database_service.dart
    ├── widgets/
    │   └── product_card.dart
    └── screens/
        ├── splash_screen.dart
        ├── onboarding_screen.dart
        ├── login_screen.dart
        ├── main_screen.dart
        ├── home_screen.dart
        ├── produk_screen.dart
        ├── detail_screen.dart
        ├── crud_screen.dart
        ├── tambah_produk_screen.dart
        ├── edit_produk_screen.dart
        └── profil_screen.dart
```

---

## URUTAN LANGKAH SETUP

### LANGKAH 1 — Buat Project Flutter Baru
Buka terminal di VS Code atau Android Studio:
```bash
flutter create va_fashion_samarinda
cd va_fashion_samarinda
```

### LANGKAH 2 — Salin pubspec.yaml
Ganti isi `pubspec.yaml` yang ada dengan file yang sudah diberikan.

### LANGKAH 3 — Install Dependencies
```bash
flutter pub get
```

### LANGKAH 4 — Buat Folder Assets
```bash
mkdir -p assets/images
```
Tambahkan baris berikut di `pubspec.yaml` (sudah ada di file):
```yaml
flutter:
  assets:
    - assets/images/
```

### LANGKAH 5 — Buat Folder & Salin File Dart

Buat folder-folder berikut di dalam `lib/`:
```
lib/models/
lib/utils/
lib/widgets/
lib/screens/
```

Salin file-file berikut **sesuai urutan**:

| Urutan | File | Lokasi |
|--------|------|--------|
| 1 | `product.dart` | `lib/models/` |
| 2 | `app_theme.dart` | `lib/utils/` |
| 3 | `database_service.dart` | `lib/utils/` |
| 4 | `product_card.dart` | `lib/widgets/` |
| 5 | `splash_screen.dart` | `lib/screens/` |
| 6 | `onboarding_screen.dart` | `lib/screens/` |
| 7 | `login_screen.dart` | `lib/screens/` |
| 8 | `main_screen.dart` | `lib/screens/` |
| 9 | `home_screen.dart` | `lib/screens/` |
| 10 | `produk_screen.dart` | `lib/screens/` |
| 11 | `detail_screen.dart` | `lib/screens/` |
| 12 | `crud_screen.dart` | `lib/screens/` |
| 13 | `tambah_produk_screen.dart` | `lib/screens/` |
| 14 | `edit_produk_screen.dart` | `lib/screens/` |
| 15 | `profil_screen.dart` | `lib/screens/` |
| 16 | `main.dart` | `lib/` |

### LANGKAH 6 — Generate Isar (WAJIB)
Isar memerlukan file generated `.g.dart`. Jalankan perintah ini:
```bash
dart run build_runner build --delete-conflicting-outputs
```
Ini akan otomatis membuat file `lib/models/product.g.dart`.

> ⚠️ Jika error, coba:
> ```bash
> flutter pub run build_runner build --delete-conflicting-outputs
> ```

### LANGKAH 7 — Jalankan Aplikasi
```bash
flutter run
```

---

## AKUN LOGIN DEMO

| Role  | Email                  | Password      |
|-------|------------------------|---------------|
| Admin | admin@vafashion.com    | vafashion123  |
| User  | user@vafashion.com     | user123       |

---

## FITUR APLIKASI

- ✅ Splash Screen dengan animasi gradient pink
- ✅ Onboarding 3 slide (hanya muncul pertama kali)
- ✅ Login dengan validasi form
- ✅ Home: katalog, kategori filter, search, promo banner
- ✅ Produk: tab kategori + favorit
- ✅ Detail Produk: foto, harga, stok, deskripsi
- ✅ CRUD Produk (Tambah, Edit, Hapus) dengan Isar DB
- ✅ Upload foto produk dari galeri
- ✅ Toggle favorit produk
- ✅ Profil toko + logout
- ✅ Bottom Navigation Bar 4 tab
- ✅ Data awal (seed) 8 produk otomatis

---

## TROUBLESHOOTING

**Error: Could not find package 'isar_flutter_libs'**
```bash
flutter pub upgrade
```

**Error: build_runner tidak ditemukan**
```bash
dart pub global activate build_runner
```

**Error: product.g.dart not found**
Pastikan sudah menjalankan:
```bash
dart run build_runner build --delete-conflicting-outputs
```

**Error: assets/images not found**
Buat folder `assets/images/` di root project (sejajar dengan `lib/`)

---

## VERSI SDK YANG DIREKOMENDASIKAN

- Flutter: 3.19.x ke atas
- Dart: 3.0.x ke atas
- Android SDK: API 21+ (Android 5.0)
- iOS: 12.0+
