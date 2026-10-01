# Pertemuan 05 Perulangan Python

Nama: Siti Auliyaatunnisaa  
NIM: 2225250085  
Kelas: 3A  

## Tujuan

Menggunakan perulangan `for` dan `while` untuk menyelesaikan masalah iteratif.

## Cara Menjalankan

```bash
python3 latihan/01_tabel_perkalian.py
python3 latihan/02_jumlah_bilangan.py
python3 latihan/03_validasi_input.py
python3 latihan/04_hitung_genap.py
python3 kuis/kuis2_deret_aritmetika.py
```
## Algoritma Kuis 2

1. Meminta pengguna memasukkan suku pertama `a`.
2. Meminta pengguna memasukkan beda `d`.
3. Meminta pengguna memasukkan banyak suku `n`.
4. Memeriksa nilai `n` menggunakan `while`.
5. Jika `n` kurang dari atau sama dengan 0, pengguna diminta memasukkan kembali nilai `n`.
6. Mengatur `total = 0` sebagai nilai awal akumulator.
7. Menggunakan perulangan `for` sebanyak `n` kali.
8. Menghitung setiap suku dengan `a + i * d`.
9. Menambahkan setiap suku ke dalam `total`.
10. Menampilkan setiap suku dan jumlah akhirnya.

## Hasil Pengujian

| No. | Input | Keluaran Aktual | Status |
|---|---|---|---|
| 1 | a = 2, d = 3, n = 5 | 2.00, 5.00, 8.00, 11.00, 14.00; Jumlah = 40.00 | Berhasil |
| 2 | a = 10, d = -2, n = 4 | 10.00, 8.00, 6.00, 4.00; Jumlah = 28.00 | Berhasil |
| 3 | a = 1.5, d = 0.5, n = 3 | 1.50, 2.00, 2.50; Jumlah = 6.00 | Berhasil |

## Refleksi

Kesalahan yang ditemukan adalah menempatkan `total = 0` di dalam perulangan. Jika `total = 0` berada di dalam loop, nilai total akan kembali menjadi 0 pada setiap iterasi sehingga jumlah seluruh suku tidak dapat terakumulasi dengan benar.

Kesalahan tersebut diperbaiki dengan menempatkan `total = 0` sebelum perulangan dimulai.
