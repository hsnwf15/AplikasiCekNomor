# CheckNumberApp
Aplikasi CheckNumberApp adalah aplikasi sederhana berbasis GUI yang dibuat menggunakan Java Swing dan NetBeans. Aplikasi ini memungkinkan pengguna memasukkan sebuah angka, kemudian memeriksa apakah angka tersebut adalah genap atau ganjil serta bilangan prima atau bukan. Aplikasi ini juga dilengkapi dengan fitur pembatasan input hanya berupa angka dan pembersihan otomatis pada field input saat mendapatkan fokus.

## Fitur Utama
- Memeriksa Genap atau Ganjil: Aplikasi dapat mendeteksi apakah angka yang dimasukkan adalah bilangan genap atau ganjil.
- Memeriksa Bilangan Prima: Aplikasi memverifikasi apakah angka tersebut termasuk bilangan prima atau bukan.
- Validasi Input: Menggunakan KeyAdapter untuk membatasi input hanya berupa angka.
- Otomatis Bersihkan Input: Menggunakan FocusListener untuk membersihkan JTextField saat mendapatkan fokus, sehingga pengguna dapat memasukkan angka baru dengan mudah.

## Komponen GUI
- JTextField - Tempat untuk memasukkan angka.
- JButton - Tombol Cek untuk memulai proses pemeriksaan.
- JLabel - Menampilkan hasil apakah angka tersebut genap atau ganjil, serta bilangan prima atau bukan.

## Cara Kerja
1. Pengguna memasukkan angka pada JTextField.
2. Aplikasi memvalidasi input agar hanya berupa angka. Karakter lain tidak akan diterima.
3. Saat JTextField mendapatkan fokus, field akan otomatis dibersihkan.
4. Pengguna menekan tombol Cek untuk menjalankan pemeriksaan.
5. Program akan memeriksa:
6. Apakah angka tersebut genap atau ganjil.
7. Apakah angka tersebut adalah bilangan prima atau bukan.
8. Hasil pemeriksaan ditampilkan pada JLabel.

## Cara Menjalankan Program
1. Buka proyek di NetBeans.
2. Pastikan semua dependensi sudah terpasang.
3. Jalankan CheckNumberFrame.java sebagai aplikasi utama.
4. Program akan terbuka dalam tampilan GUI.

## Struktur Kode
- checkNumber(): Fungsi utama yang menangani logika pemeriksaan genap/ganjil dan bilangan prima.
- isPrime(): Fungsi untuk memverifikasi apakah angka merupakan bilangan prima.
- KeyListener pada inputField: Mencegah input karakter non-numerik.
- FocusListener pada inputField: Membersihkan JTextField saat mendapatkan fokus.

## Screenshot berjalannya Program
![Screenshot berjalannya Program](images.png)

## Contoh Penggunaan
1. Masukkan angka pada JTextField.
2. Klik tombol Cek.
3. Jika input valid, JLabel akan menampilkan hasil apakah angka tersebut genap atau ganjil serta bilangan prima atau bukan.

## Persyaratan Sistem
- Java Development Kit (JDK) versi 8 atau lebih baru.
- NetBeans IDE atau editor Java lainnya.

## Lisensi
Proyek ini bebas digunakan untuk keperluan belajar dan pengembangan lebih lanjut.
