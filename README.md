# Pertemuan 5: Aplikasi Pertama dan Widget Dasar Flutter

**NIM**: 2341720116
**Nama**: Hanif Faishal Hilmi

---

## 📝 Praktikum #05 | Aplikasi Pertama dan Widget Dasar Flutter

---

### Praktikum 1: Membuat Project Flutter Baru

**Langkah 1**
Buka VS Code, lalu tekan **Ctrl + Shift + P**, ketik **Flutter**, pilih **New Application Project**.

![alt text](/img/praktikum1/P5_praktikum1_1.png)

**Langkah 2**
Buat folder sesuai style laporan, lalu pilih **Select a folder to create the project in**.

![alt text](/img/praktikum1/P5_praktikum1_2.png)

**Langkah 3**
Buat nama project `hello_world`, lalu tekan **Enter**. Tunggu hingga selesai.

![alt text](/img/praktikum1/P5_praktikum1_3.png)

**Langkah 4**
Jika berhasil, akan muncul pesan **"Your Flutter Project is ready!"**.

---

### Praktikum 2: Menghubungkan Perangkat Android atau Emulator

#### VS Code

**Mengaktifkan proses debug USB**

1. Di perangkat Android, buka **Settings > About phone**.
2. Ketuk **Build number** tujuh kali hingga muncul pesan **You are now a developer!**.

![alt text](img/praktikum2/P5_praktikum2_1.jpg)
![alt text](img/praktikum2/P5_praktikum2_2.jpg)

3. Kembali ke **Settings > System > Developer options**.
4. Aktifkan **USB Debugging**.

![alt text](img/praktikum2/P5_praktikum2_3.jpg)
![alt text](img/praktikum2/P5_praktikum2_4.jpg)
![alt text](img/praktikum2/P5_praktikum2_5.jpg)


#### Android Studio

1. Di Android Studio, klik Tools > SDK Manager. Dialog Preferences > Appearance & Behavior > System Settings > Android SDK akan terbuka.

2. Klik tab SDK Tools.

3. Pilih Google USB Driver, lalu klik OK.


![alt text](img/praktikum2/P5_praktikum2_6.png)
![alt text](img/praktikum2/P5_praktikum2_7.png)

---

#### Menjalankan aplikasi di perangkat Android menggunakan kabel

1. Sambungkan perangkat Android ke komputer menggunakan kabel USB. Dialog yang meminta Anda mengizinkan proses debug USB akan muncul di perangkat.

![alt text](img/praktikum2/P5_praktikum2_3_1.jpg)

2. Pilih kotak centang Always allow from this computer, lalu ketuk OK.

3. Di Android Studio di komputer, pastikan perangkat Anda dipilih di menu dropdown. Klik Ini adalah ikon Run Android Studio.

### Praktikum 3: Membuat Repository GitHub dan Laporan Praktikum

**Langkah 1**
Login GitHub, buat repository baru bernama **flutter-fundamental-part1**.

![alt text](img/praktikum3/praktikum3_1.png)

**Langkah 2**
Repository berhasil dibuat.

![alt text](img/praktikum3/praktikum3_2.png)

**Langkah 3**
Di VS Code, buka terminal lalu inisialisasi git.

![alt text](img/praktikum3/praktikum3_3.png)

**Langkah 4**
Pilih menu Source Control, lalu stage file `.gitignore`.

![alt text](img/praktikum3/praktikum3_4.png)

**Langkah 5**
Commit dengan pesan *"tambah gitignore"*.

![alt text](img/praktikum3/praktikum3_5.png)

**Langkah 6**
Push project ke GitHub.

![alt text](img/praktikum3/praktikum3_6.png)

**Langkah 7**
Tambahkan remote repository.

![alt text](img/praktikum3/praktikum3_7.png)

**Langkah 8**
Masukkan URL repository dan beri nama remote `origin`.

![alt text](img/praktikum3/praktikum3_8_1.png)
![alt text](img/praktikum3/praktikum3_8_2.png)

**Langkah 9**
Push file `README.md`, gunakan token GitHub untuk login.

![alt text](img/praktikum3/praktikum3_9_1.png)
![alt text](img/praktikum3/praktikum3_9_2.png)
![alt text](img/praktikum3/praktikum3_9_3.png)
![alt text](img/praktikum3/praktikum3_9_4.png)

**Langkah 10**
Stage All Changes, commit dengan pesan *"project hello\_world"*, lalu push.

![alt text](img/praktikum3/praktikum3_10.png)

**Langkah 11**
Jalankan project di emulator atau Chrome.

![alt text](img/praktikum3/praktikum3_11.png)
![alt text](img/praktikum3/praktikum3_11_1.png)

**Langkah 12**
Screenshot hasil dengan teks nama lengkap Anda. Simpan sebagai `01.png` di folder `images`. Tambahkan ke `README.md` lalu push.

![alt text](/image/01.png)

---

### Praktikum 4: Menerapkan Widget Dasar

**Langkah 1: Text Widget**
Buat folder `basic_widgets` di dalam `lib`, lalu file `text_widget.dart`. Import ke `main.dart`.

![alt text](img/praktikum4/praktikum4_1_1.png)
![alt text](img/praktikum4/praktikum4_1_2.png)

**Langkah 2: Image Widget**
Buat file `image_widget.dart` dan tambahkan asset pada `pubspec.yaml`.

![alt text](img/praktikum4/praktikum4_2_1.png)
![alt text](img/praktikum4/praktikum4_2_2.png)

---

### Praktikum 5: Menerapkan Widget Material Design dan iOS Cupertino

**Langkah 1: Cupertino Button dan Loading Bar**
Buat file `loading_cupertino.dart`.

![alt text](img/praktikum5/praktikum5_1.png)

**Langkah 2: Floating Action Button (FAB)**
Buat file `fab_widget.dart`.

![alt text](img/praktikum5/praktikum5_2.png)

**Langkah 3: Scaffold Widget**
Gunakan `Scaffold` untuk tata letak Material Design.

![alt text](img/praktikum5/praktikum5_3.png)

**Langkah 4: Dialog Widget**
Gunakan `AlertDialog` atau `SimpleDialog`.

![alt text](img/praktikum5/praktikum5_4.png)

**Langkah 5: Input dan Selection Widget**
Contoh penggunaan `TextField`.

![alt text](img/praktikum5/praktikum5_5.png)

**Langkah 6: Date and Time Pickers**
Gunakan widget pemilih tanggal dan waktu.

![alt text](img/praktikum5/praktikum5_6_1.png)
![alt text](img/praktikum5/praktikum5_6_2.png)
![alt text](img/praktikum5/praktikum5_6_3.png)

---

