# Pertemuan 06 Nested Loop, Pola, Akumulasi, dan Pencacahan

## Identitas

- Nama: Nailah Nur Fadilah
- NIM: 2225250163
- Kelas: 3E

## Tujuan

Menerapkan nested loop dalam Python untuk membuat pola, mengolah pasangan data, melakukan akumulasi, dan pencacahan.

## Struktur Program

Program terdiri dari beberapa latihan dan satu tugas utama:

- `latihan/01_pasangan_indeks.py`
- `latihan/02_pola_segitiga.py`
- `latihan/03_jumlah_per_baris.py`
- `latihan/04_hitung_pasangan.py`
- `tugas/tabel_perkalian_dan_statistik.py`

## Cara Menjalankan Program

Pastikan terminal berada di folder utama Pertemuan 06.

Contoh menjalankan latihan:

```bash
python latihan/01_pasangan_indeks.py
Algoritma Tugas 3

Program Tugas 3 menggunakan nested loop untuk membuat tabel perkalian berukuran n × n.

Perulangan luar (i) digunakan untuk mengatur baris tabel.
Perulangan dalam (j) digunakan untuk mengatur kolom tabel.
Setiap hasil perkalian dihitung dengan i * j.
total_semua digunakan sebagai accumulator untuk menjumlahkan seluruh hasil perkalian.
total_baris digunakan untuk menghitung jumlah hasil pada setiap baris.
count_genap digunakan sebagai counter untuk menghitung banyak hasil perkalian yang bernilai genap.
Hasil genap diperiksa menggunakan kondisi hasil % 2 == 0.
Hasil Pengujian
Input	Hasil yang Diharapkan	Hasil Aktual	Status
n = 1	Total = 1, Genap = 0	Total = 1, Genap = 0	Berhasil
n = 2	Total = 9, Genap = 3	Total = 9, Genap = 3	Berhasil
n = 3	Total = 36, Genap = 5	Total = 36, Genap = 5	Berhasil
Analisis Efisiensi

Untuk input n, perulangan dalam dijalankan sebanyak n kali untuk setiap perulangan luar. Karena perulangan luar juga berjalan sebanyak n kali, maka bagian utama nested loop dieksekusi sebanyak:

n × n = n²

Contohnya, jika n = 3, maka isi perulangan dalam dijalankan sebanyak 3 × 3 = 9 kali.

Refleksi

Salah satu kesalahan yang perlu diperhatikan dalam nested loop adalah penempatan perulangan dalam dan perintah print(). Jika indentasi tidak tepat, pola yang dihasilkan dapat berbeda dari yang diharapkan. Kesalahan tersebut diperbaiki dengan memastikan perulangan dalam berada di dalam perulangan luar dan print() untuk berpindah baris diletakkan pada posisi yang sesuai.

Kesimpulan

Melalui latihan dan tugas pada Pertemuan 06, nested loop dapat digunakan untuk mengolah pasangan data, membuat pola, menghitung jumlah setiap baris, serta melakukan akumulasi dan pencacahan pada tabel perkalian.
## Catatan Pengujian

Seluruh program telah dijalankan dan diuji menggunakan beberapa nilai input sesuai dengan ketentuan tugas. Hasil pengujian menunjukkan bahwa program dapat berjalan sesuai dengan hasil yang diharapkan.