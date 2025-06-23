Muhamad Farhan - 4522210057

# Tanya Daku

Aplikasi ini akan menampilkan gambar bola secara acak ketika gambar bola diklik.

## main()
Fungsi ini menjalankan aplikasi dan `TanyaDakuApp`.

## TanyaDakuApp
Widget utama aplikasi dan mengarahkan ke `HalamanBola`.

## HalamanBola
- Struktur utama aplikasi
- Terdapat `AppBar` dengan judul "Tanya Daku Apa Saja' dengen latar belakang halaman berwarna biru.
- `Body` diisi oleh widget `Bola`.

## Bola
- `StatefulWidget` yang artinya tampilan dapat berubah tergantung pemakaian.
- Variabel `NomorBola` untuk menyimpan angka acak dari 1 sampai 5, lalu akan menampilkan gambar bola sesuai dari `ball1.png` sampai dengan `ball5.png`.

# Langkah-Langkah Menjalankan Project
Pastikan kamu sudah menginstall dependensi terlebih dahulu:

```bash
flutter pub get
```

Jalankan aplikasi:

```bash
flutter run
```
