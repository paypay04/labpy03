PENJELASAN CODINGAN PERTAMA

1. generate_numbers(n) adalah fungsi yang:
   - Menerima parameter n (jumlah angka yang ingin dihasilkan)
   - Menggunakan perulangan while untuk menghasilkan n angka acak
   - Hanya mencetak angka jika nilainya < 0.5 menggunakan random()
   - Menampilkan output berformat "data ke: [nomor] => [angka acak]"

2. main() adalah fungsi utama yang:
   - Meminta input dari pengguna ("Masukkan nilai N: ")
   - Memanggil fungsi generate_numbers dengan input tersebut
   - Memiliki penanganan error (try-except) untuk input yang tidak valid
   - Mencetak "Selesai" jika program berhasil dijalankan

Dari output yang terlihat di terminal, program dijalankan dengan input N=5 dan berhasil menghasilkan 5 angka acak beserta keterangannya.
Program ini bisa berguna untuk keperluan simulasi atau pengujian yang membutuhkan angka acak dengan batasan nilai tertentu (dalam hal ini < 0.5).

PENJELASAN CODINGAN KEDUA

Inisialisasi awal:

Modal awal = 100.000.000
Total laba dimulai dari 0
List kosong untuk menyimpan laba per bulan

Perhitungan laba per bulan:

Bulan 1-2: Tidak ada laba (0%)
Bulan 3-4: Laba 1% dari modal (1.000.000)
Bulan 5-7: Laba 5% dari modal (5.000.000)
Bulan 8: Laba 2% dari modal (2.000.000)

Proses dan output:

Menggunakan loop untuk menghitung 8 bulan
Setiap bulan ditampilkan "Laba bulan ke-X sebesar: Y"
Di akhir menampilkan total laba keseluruhan

Dari output yang terlihat, program berhasil menghitung dan menampilkan laba per bulan serta total laba sebesar 19.000.000.


PENJELASAN CODINGAN KETIGA

Program ini mensimulasikan mesin ATM sederhana dengan fitur penarikan uang. Berikut penjelasannya :

Menu Utama:

Menampilkan saldo saat ini
Pilihan 1: Tarik Uang
Pilihan 2: Keluar dari ATM

Fitur Tarik Uang (Pilihan 1):

Meminta input jumlah yang ingin ditarik
Melakukan validasi:

Jika jumlah > saldo: Menampilkan "Maaf, saldo tidak mencukupi!"
Jika jumlah ≤ 0: Menampilkan "Jumlah penarikan tidak valid!"
Jika input bukan angka: Menampilkan "Mohon masukkan angka yang valid"

Jika valid: Mengurangi saldo dan menampilkan "Penarikan berhasil!"

Keluar (Pilihan 2):

Menampilkan pesan terima kasih
Mengakhiri program

Dari output yang terlihat, program berjalan dengan benar - menunjukkan saldo awal Rp 100.000, berhasil melakukan penarikan, dan menangani kasus saldo tidak mencukupi dengan tepat.
