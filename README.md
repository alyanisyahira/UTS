
# 🕌 HalalFinder

HalalFinder adalah aplikasi mobile berbasis *Flutter* yang dirancang untuk membantu pengguna menemukan informasi terkait produk, restoran, atau tempat yang memiliki status halal. Aplikasi ini memiliki sistem autentikasi sederhana dan beberapa halaman utama seperti Login, Home, Detail, dan Profile.

---

## 🚀 Fitur Utama

- **Login Screen** – Halaman autentikasi pengguna.
- **Home Screen** – Menampilkan daftar produk atau tempat halal.
- **Detail Screen** – Menampilkan informasi detail produk atau tempat.
- **Profile Screen** – Menampilkan profil dan pengaturan pengguna.
- **Dark Theme** – Tampilan modern dengan tema gelap, dikelola melalui file `app_theme.dart`.

---

## 🧱 Struktur Folder

```

lib/
│
├── main.dart                # Entry point aplikasi
│
├── screens/                 # Berisi semua tampilan (UI)
│   ├── login_screen.dart
│   ├── home_screen.dart
│   ├── detail_screen.dart
│   └── profile_screen.dart
│
└── theme/
└── app_theme.dart       # File konfigurasi tema aplikasi

````

---

## ⚙️ Cara Menjalankan Proyek

### 1. Pastikan Prasyarat Berikut Terinstal:
- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- [Dart SDK](https://dart.dev/get-dart)
- Android Studio / VS Code (dengan Flutter plugin)
- Emulator Android atau perangkat fisik

### 2. Clone Repository:
```bash
git clone https://github.com/alyanisyahira/UTS.git
````

### 3. Masuk ke Folder Proyek:

```bash
cd UTS
```

### 4. Jalankan Aplikasi:

```bash
flutter pub get
flutter run
```

---

## 🖥️ Route dan Navigasi

Aplikasi menggunakan **Named Routes** untuk berpindah antar halaman.

| Route      | Halaman Tujuan | File Asal                     |
| ---------- | -------------- | ----------------------------- |
| `/login`   | LoginScreen    | `screens/login_screen.dart`   |
| `/home`    | HomeScreen     | `screens/home_screen.dart`    |
| `/detail`  | DetailScreen   | `screens/detail_screen.dart`  |
| `/profile` | ProfileScreen  | `screens/profile_screen.dart` |

---

## 🎨 Tema Aplikasi

Tema aplikasi diatur dalam file `app_theme.dart`, menggunakan **Dark Mode** sebagai tampilan utama.
Warna primer, sekunder, serta gaya teks dapat disesuaikan sesuai kebutuhan proyek.

---

## 👩‍💻 Kontributor

* **Alyani Syahira**
  Mahasiswa Teknik Informatika, UIN Malang.

---

## 📜 Lisensi

Proyek ini bersifat open-source dan dapat digunakan untuk keperluan pembelajaran.

```

---

Kamu cukup buat file baru di folder proyekmu dengan nama **`README.md`**, lalu **paste** isi di atas.  
Ingin saya tambahkan juga **preview tampilan aplikasi (misal screenshot layout contoh)** dalam README ini?
```
