# 📝 Praktikum \#05: Aplikasi Pertama dan Widget Dasar Flutter

  - **NIM**: `2341720116`
  - **Nama**: `Hanif Faishal Hilmi`

-----

## Praktikum 1: Membuat Project Flutter Baru

### Langkah 1: Membuka Command Palette

Membuka VS Code, kemudian tekan `Ctrl + Shift + P` untuk menampilkan **Command Palette**. Ketik `Flutter` dan pilih **New Application Project**.

### Langkah 2: Memilih Lokasi Proyek

Memilih folder tujuan untuk menyimpan proyek.

### Langkah 3: Memberi Nama Proyek

Memberi nama proyek `hello_world` dan tekan **Enter**. Proses pembuatan proyek akan berjalan secara otomatis.

### Langkah 4: Proyek Berhasil Dibuat

Setelah selesai, akan muncul pesan "**Your Flutter Project is ready\!**" yang menandakan proyek baru telah berhasil dibuat.

-----

## Praktikum 2: Menghubungkan Perangkat Android

### Langkah 1-6: Mengaktifkan Opsi Pengembang dan Debug USB

Untuk menghubungkan perangkat Android fisik, **Opsi Pengembang (Developer Options)** dan **Debug USB (USB Debugging)** harus diaktifkan melalui menu **Settings** pada perangkat.

-----

## Praktikum 3: Menggunakan GitHub untuk Version Control

### Langkah 1-2: Membuat Repository Baru

Membuat *repository* baru di GitHub dengan nama `flutter-fundamental-part1`.

### Langkah 3-10: Inisialisasi Git dan Push Proyek Awal

Melakukan inisialisasi Git pada proyek `hello_world` melalui terminal VS Code. Kemudian, melakukan *commit* dan *push* untuk file `.gitignore`, `README.md`, dan seluruh file proyek lainnya ke *repository* GitHub.

### Langkah 11: Menjalankan Aplikasi Pertama

Menjalankan proyek `hello_world` pada emulator atau perangkat. Aplikasi *counter* bawaan Flutter akan tampil sebagai hasilnya.

### Langkah 12: Modifikasi dan Personalisasi README

Mengubah teks pada aplikasi menjadi nama lengkap, mengambil *screenshot*, dan menampilkannya pada file `README.md` di *repository* GitHub.

-----

## Praktikum 4: Menerapkan Widget Dasar

### Langkah 1: Text Widget

Membuat file `text_widget.dart` di dalam folder `lib/basic_widgets` dan mengimplementasikannya di `main.dart` untuk menampilkan teks yang sudah di-styling.

### Langkah 2: Image Widget

Menambahkan gambar `logo_polinema.jpg` ke dalam folder `assets`, mendaftarkannya di `pubspec.yaml`, dan membuat `image_widget.dart` untuk menampilkannya di aplikasi.

-----

## Praktikum 5: Menerapkan Widget Material Design & Cupertino

### Langkah 1: Cupertino Widgets

Membuat file `loading_cupertino.dart` untuk menampilkan `CupertinoButton` dan `CupertinoActivityIndicator`.

### Langkah 2: Floating Action Button (FAB)

Membuat file `fab_widget.dart` untuk mengimplementasikan `FloatingActionButton` sebagai bagian dari Material Design.

### Langkah 3: Scaffold Widget

Menggunakan `Scaffold` di `main.dart` untuk membangun struktur dasar halaman sesuai standar Material Design, yang mencakup `AppBar`, `body`, dan `bottomNavigationBar`.

### Langkah 4: Dialog Widget

Mengubah `main.dart` untuk menampilkan `AlertDialog` atau `SimpleDialog` saat sebuah aksi dipicu.

### Langkah 5: Input Widget (TextField)

Mengimplementasikan `TextField` untuk menerima input teks dari pengguna.

### Langkah 6: Date and Time Pickers

Menambahkan fungsionalitas untuk menampilkan pemilih tanggal (*Date Picker*) dan waktu (*Time Picker*) sebagai bagian dari input pengguna.
