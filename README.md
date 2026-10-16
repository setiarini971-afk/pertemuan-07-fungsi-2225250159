# Pertemuan 07 Fungsi Python

Nama: [Nama lengkap]
NIM: [NIM]
Kelas: [Kelas]

## Tujuan
Menggunakan fungsi, parameter, return value, dan scope
untuk membuat program Python yang modular.

## Cara Menjalankan
Jalankan latihan dari terminal VS Code menggunakan perintah:

python latihan/01_salam.py
python latihan/02_luas_persegi_panjang.py
python latihan/03_jumlah_n.py
python latihan/04_statistik_sederhana.py
python latihan/05_scope.py

Untuk menjalankan Praktik 2:

python praktik/utilitas_matematika.py

## Struktur Fungsi
- salam(nama, kelas): menampilkan salam dan kelas.
- luas_persegi_panjang(p, l): mengembalikan luas persegi panjang.
- jumlah_n(n): mengembalikan jumlah bilangan 1 sampai n.
- statistik(data): mengembalikan nilai minimum, maksimum,
  dan rata-rata.
- demo(x): menunjukkan penggunaan local scope.
- luas_segitiga(a, t): mengembalikan luas segitiga.
- faktorial(n): mengembalikan nilai faktorial.
- tampilkan_menu(): menampilkan pilihan operasi.

## Hasil Pengujian
| Fungsi | Input | Hasil yang diharapkan | Status |
|---|---|---|---|
| luas_persegi_panjang | 8, 5 | 40 | [Isi setelah diuji] |
| luas_segitiga | 10, 6 | 30.0 | [Isi setelah diuji] |
| jumlah_n | 10 | 55 | [Isi setelah diuji] |
| faktorial | 5 | 120 | [Isi setelah diuji] |
| faktorial | 0 | 1 | [Isi setelah diuji] |

## Refleksi
Penggunaan fungsi membuat program lebih mudah dibaca
karena setiap fungsi memiliki tugas masing-masing.
Parameter digunakan untuk menerima data, sedangkan
return digunakan untuk mengembalikan hasil perhitungan.
Scope juga membantu membatasi penggunaan variabel
di dalam fungsi.