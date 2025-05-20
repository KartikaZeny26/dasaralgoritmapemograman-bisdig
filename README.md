*STUDI KASUS 1*: Faktorial Menggunakan Rekursi
fungsi adalah blok kode terpisah yang digunakan untuk melakukan tugas tertentu. fungsi membantu:
Modularitas: memecah program menjadi bagian-bagian kecil yang mudah dikelola.
Reusabilitas: fungsi dapat dipanggil berulang kali dari mana saja dalam program.
Abstraksi: menyambungkan detail implementasi, sehingga kita bisa fokus pada apa yang dilakukan
Rekursi adalah teknik programan dimana sebuah fungsi memanggil dirinya sendiri. Dalam faktorial, n! = n * (n-1)!, sehingga bisa dihitung dengan memanggila fungsi itu sendiri dengan nilai yang lebih kecil sampai n = 1.


*STUDI KASUS 2*: Input Nilai dan Mencari Nilai Tertinggi
Perulangan yaitu memungkinkan kita mengeksekusi blok kode berulang kali. Dalam kasus ini, kita ingin menerima input nilai 5 siswa - menggunakan for loop agara efesien.
List/Array adalah struktur data di Python yang dapat menyimpan sekumpulan nilai dalam satu variabel. kita menyimpan seluruh nilai siswa dalam list agar bisa dianalisis (misalnya dengan max() untuk memcari nilai tertinggi).


*STUDI KASUS 3*: Diskon pada Sistem E-Commerce
Struktur Kontrol Percabangan (if,else) digunakan untuk membuat keputusan berdasarkan suatu kondisi.
Dalam kasus ini: Jika total belanja > 500.000, maka pelanggan mendapat diskon 10%.
Logika Diskon:
jika total belanja lebih dari 500.000:
total_bayar = total_belanja * 0.9
jika tidak:
total_bayar = total_belanja


*STUDI KASUS 4*: Menghitung Total Harga Pembelian 3 Barang

Seorang kasir toko ingin sistem sederhana untuk menghitung total harga pembelian 3 barang dan menampilkan totalnya.

## Langkah-langkah Algoritma

1. Mulai.
2. Input harga barang pertama.
3. Input harga barang kedua.
4. Input harga barang ketiga.
5. Hitung total harga ketiga barang.
6. Tampilkan total pembayaran.
7. Selesai.

## Program Python

File kasir.py berisi kode Python sederhana yang membaca harga 3 barang dari pengguna, lalu menghitung dan menampilkan total pembayaran.

### Cara Menjalankan

1. Buka terminal atau command prompt.
2. Jalankan program dengan:

bash
python kasir.py


**STUDI KASUS 5**: Penentuan Kelulusan Siswa Berdasarkan Rata-Rata Nilai

Seorang siswa ingin mengetahui apakah nilai ujiannya memenuhi syarat lulus berdasarkan rata-rata nilai dari 3 mata pelajaran.

## Penjelasan

### Peran Tipe Data
- `float` digunakan untuk menangani nilai yang memiliki desimal.
- `str` digunakan untuk menyimpan teks seperti status "Lulus".

### Peran Operator
- Operator aritmatika `+` dan `/` digunakan untuk menghitung rata-rata.
- Operator relasional `>=` digunakan untuk menentukan kelulusan.

## Program Python
File `kelulusan.py` berisi program untuk:
1. Menerima input 3 nilai mata pelajaran.
2. Menghitung rata-rata nilai.
3. Menentukan apakah siswa lulus (rata-rata ≥ 75).
4. Menampilkan rata-rata dan status kelulusan.

### Cara Menjalankan

bash
python kelulusan.py
