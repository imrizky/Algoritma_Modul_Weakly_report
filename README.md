> ```
> Nama : Firnanda Rizki Pratama
> NIM  : 24343008
> Prody: Informatika
> ```

---


# Algoritma_Modul

# Modul 1
#Apa itu Algoritma 
adalah serangkaian langkah-langkah atau instruksi yang sistematis dan terstruktur untuk menyelesaikan suatu masalah atau mencapai tujuan tertentu. Dalam pengertian yang lebih teknis, algoritma adalah urutan instruksi atau prosedur yang jelas, yang dapat dieksekusi untuk menghasilkan solusi dari suatu masalah.

Karakteristik Algoritma:
Langkah-langkah yang Terdefinisi dengan Jelas: Setiap langkah dalam algoritma harus jelas dan tidak ambigu. Instruksi yang diberikan harus mudah dipahami dan diterjemahkan ke dalam kode oleh komputer.

Terstruktur: Algoritma harus mengikuti urutan yang logis dan terstruktur. Tidak boleh ada langkah yang hilang atau tumpang tindih dalam proses penyelesaian masalah.

Input dan Output: Algoritma menerima input, yaitu data yang diberikan untuk diproses, dan menghasilkan output, yaitu hasil dari pemrosesan data tersebut.

Akhir yang Jelas: Algoritma harus memiliki titik akhir yang jelas. Artinya, algoritma harus berhenti setelah menjalankan serangkaian langkah.

Efisien: Algoritma harus dapat menyelesaikan masalah dengan cara yang efisien dalam hal waktu dan sumber daya.

Contoh Algoritma:
Misalnya, kita ingin mencari nilai maksimum dalam sebuah array (deretan angka):

Input: Sebuah array dengan elemen-elemen angka.
Langkah 1: Tentukan nilai maksimum sementara, misalnya nilai pertama dari array.
Langkah 2: Bandingkan nilai maksimum sementara dengan setiap elemen dalam array.
Langkah 3: Jika ditemukan nilai yang lebih besar, perbarui nilai maksimum sementara.
Langkah 4: Lanjutkan hingga semua elemen array diperiksa.
Output: Nilai maksimum dari array.

# Modul 2
Mengajarakan tentang Program dasar yang mana berisi tentang Program halo siapa nama mu penjelasan sedikit tentang program 
## Deklarasi variable

char nama[100]; digunakan untuk menyimpan nama lengkap yang dimasukkan oleh pengguna. Ukuran array 100 dipilih untuk memastikan cukup besar untuk menampung nama yang panjang.
## Input Nama:

Program meminta pengguna untuk menginputkan nama dengan printf("Hello, siapa nama lengkapmu? ");.
Input nama dilakukan dengan fgets(nama, sizeof(nama), stdin);, yang memungkinkan pengguna memasukkan nama lengkap (termasuk spasi).
## Output:

Setelah mendapatkan input dari pengguna, program akan menampilkan pesan selamat datang dengan printf("Selamat Datang, %s dalam Pemrograman C!\n", nama);.
%s digunakan dalam format string untuk menampilkan nilai yang tersimpan dalam variabel nama.
## Modul_2
pada modul ini kita di berikan untuk membuat data secara dinamus dan menghitug nilai akhir sesuai dengan rumus yang telah di berikan 

## Penjelasan Tentang Program

## Deklarasi Variabel:

char nama[100], prodi[100], fakultas[100]; untuk menyimpan nama, program studi, dan fakultas dalam bentuk string.
int nim; untuk menyimpan NIM mahasiswa.
float nilaiPraktikum, nilaiUTS, nilaiUAS, nilaiAkhir; untuk menyimpan nilai praktikum, UTS, UAS, dan menghitung nilai akhir.

## Input Data:

Program meminta input untuk nama, NIM, program studi, fakultas, nilai praktikum, nilai UTS, dan nilai UAS.
Fungsi fgets() digunakan untuk memasukkan string yang mengandung spasi seperti nama, program studi, dan fakultas.
Fungsi scanf() digunakan untuk memasukkan nilai numerik (NIM, nilai praktikum, UTS, dan UAS).

## Menghitung Nilai Akhir:

Nilai akhir dihitung menggunakan rumus yang diberikan:

Nilai Akhir = (30% * Nilai Praktikum) + (30% * Nilai UTS) + (40% * Nilai UAS)
Perhitungan ini dilakukan dengan mengalikan setiap nilai dengan bobot yang sesuai, yaitu 30% untuk nilai praktikum dan UTS, serta 40% untuk nilai UAS.
Menampilkan Hasil:

Setelah perhitungan selesai, program menampilkan hasil input dan nilai akhir yang dihitung.

# Modul_2_3
