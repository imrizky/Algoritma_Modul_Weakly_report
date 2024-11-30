> ```
> Nama : Firnanda Rizki Pratama
> NIM  : 24343008
> Prody: Informatika
> ```

---
  <div align="center">
    <img src="https://media.giphy.com/media/dWesBcTLavkZuG35MI/giphy.gif" width="600" height="300"/>
  </div>

# <picture><img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width = 50px></picture>    Algoritma_Modul

## <picture><img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width = 50px></picture>  Modul 1
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

## <picture><img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width = 50px></picture> # Modul 2
Mengajarakan tentang Program dasar yang mana berisi tentang Program halo siapa nama mu penjelasan sedikit tentang program 
## Deklarasi variable

char nama[100]; digunakan untuk menyimpan nama lengkap yang dimasukkan oleh pengguna. Ukuran array 100 dipilih untuk memastikan cukup besar untuk menampung nama yang panjang.
## Input Nama:

Program meminta pengguna untuk menginputkan nama dengan printf("Hello, siapa nama lengkapmu? ");.
Input nama dilakukan dengan fgets(nama, sizeof(nama), stdin);, yang memungkinkan pengguna memasukkan nama lengkap (termasuk spasi).
## Output:

Setelah mendapatkan input dari pengguna, program akan menampilkan pesan selamat datang dengan printf("Selamat Datang, %s dalam Pemrograman C!\n", nama);.
%s digunakan dalam format string untuk menampilkan nilai yang tersimpan dalam variabel nama.
# Modul_2_2
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
Pada modul 2_3 ini memberikan cara yang sederhana dan langsung untuk menghitung luas segitiga dengan memasukan nilai alas dan tinggi 

## Deklarasi Variabel:

float alas = 8.0; untuk panjang alas segitiga (dalam cm).
float tinggi = 5.0; untuk tinggi segitiga (dalam cm).
float luas; untuk menyimpan hasil perhitungan luas.

## Perhitungan Luas:

Program menggunakan rumus untuk menghitung luas segitiga:
Luas
= 1  × Alas x Tinggi Luas=  2
​  2                         1 
 ×Alas×Tinggi
Di dalam program ini, rumus ditulis sebagai luas = 0.5 * alas * tinggi;.

## Menampilkan Hasil:

Program menampilkan panjang alas, tinggi, dan luas segitiga dalam satuan cm dan cm².

# Modul 2_4
Disini di jelaskan tentang cara sedehana dan langsung untuk menghitung luas persegi panjang dengan memasukan nilai dari panjang dan lebar

## Deklarasi Variabel:

float panjang = 10.0; untuk panjang persegi panjang (dalam cm).
float lebar = 5.0; untuk lebar persegi panjang (dalam cm).
float luas; untuk menyimpan hasil perhitungan luas.

## Perhitungan Luas:

Program menggunakan rumus untuk menghitung luas persegi panjang:
Luas = Panjang × Lebar
Luas=Panjang×Lebar
Di dalam program ini, rumus ditulis sebagai luas = panjang * lebar;.

## Menampilkan Hasil:
/
Program menampilkan panjang, lebar, dan luas persegi panjang dalam satuan cm dan cm².

## <picture><img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width = 50px></picture># Modul 3
Pada modul ini Belajar tentag Variable, Konstata dan Tipe Data
Inti dari sebuah program komputer adalah menerima input, melakukan
pemrosesan, dan menghasilkan output. Nilai input bisa kita dapatkan dari
keyboard, file, kamera, mikrofon, dan sebagainya. Sementara output dapat kita
tampilkan ke monitor, cetak ke dokumen, atau ke dalam sebuah file. Pada tahap pemrosesan, program membutuhkan bantuan variabel untuk menyimpan nilai
sementara.

# Modul 3_1
Program ini Memungkinkan untuk dapat mengkonversilan nilai rupiah yang berbeda-beda, cukup dengan memasukan jumlah rupiah yang di inginkan

## Deklarasi Variabel:

float rupiah; untuk menyimpan jumlah uang dalam Rupiah yang ingin dikonversi.
float dollar; untuk menyimpan hasil konversi ke Dollar.
float kurs = 14250.0; adalah nilai tukar (kurs) dari Rupiah ke Dollar (1$ = Rp 14.250).

## Input Uang dalam Rupiah:

Program meminta pengguna untuk memasukkan jumlah uang dalam Rupiah dengan scanf("%f", &rupiah);.

## Konversi Rupiah ke Dollar:

Uang dalam Rupiah dibagi dengan kurs untuk mendapatkan nilai dalam Dollar: dollar = rupiah / kurs;.

## Output:

Program menampilkan hasil konversi dalam format Rupiah dan Dollar dengan dua angka di belakang koma menggunakan printf.

# Modul 3_2
Pada Modul ini di sama saja dengan modul 3_1 hanya saja disini mengkonversikan suhu yakni memungkin kan mengkonveresikan suhu ke nilai celcius, nilai suhu bebas di masukan berapa saja yang ingin di masukan oleh pengguna 

Deklarasi Variabel:

float celsius; untuk menyimpan suhu yang dimasukkan oleh pengguna dalam Celcius.
float kelvin, fahrenheit, reamur; untuk menyimpan hasil konversi suhu ke Kelvin, Fahrenheit, dan Reamur.
Input Suhu dalam Celcius:

Program meminta pengguna untuk memasukkan suhu dalam Celcius menggunakan scanf("%f", &celsius);.
Perhitungan Konversi:

## Konversi ke Kelvin: 
𝐾 = 𝐶 + 273.15
K=C+273.15
## Konversi ke Fahrenheit: 
𝐹 = ( 𝐶 × 1.8 ) + 32

## Konversi ke Reamur: 
𝑅 = 𝐶 × 0.8

## Menampilkan Hasil:


Program menampilkan hasil konversi suhu ke Kelvin, Fahrenheit, dan Reamur dengan dua angka di belakang koma menggunakan printf.

# Modul 3_3
Pada modul 3_3 ini memberikan cara yang sederhana untuk menghitung Volume dal Luas permukaan bola menggunakan rumus yang telah di tentukan 

## Konstanta PI:

#define PI 3.14159 mendefinisikan konstanta 
𝜋
π dengan nilai 3.14159, yang digunakan dalam perhitungan.

## Deklarasi Variabel:

float diameter = 12.0; untuk panjang diameter bola (dalam cm).
float radius = diameter / 2; untuk menghitung jari-jari bola.
float volume, surface_area; untuk menyimpan hasil perhitungan volume dan luas permukaan.

## Perhitungan Volume:

Rumus volume bola:
Volume
= 4  × 𝜋 × 𝑟 3 ​                         
  3
 
Volume dihitung dengan rumus tersebut, menggunakan jari-jari bola.

## Perhitungan Luas Permukaan:

Rumus luas permukaan bola:
Luas Permukaan = 4 × 𝜋 × 𝑟 2
 
 
Luas permukaan dihitung dengan rumus tersebut, menggunakan jari-jari bola.

## Menampilkan Hasil:

Program menampilkan hasil diameter, jari-jari, volume, dan luas permukaan bola dengan dua angka di belakang koma.

## <picture><img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/about_me.gif?raw=true" width = 50px></picture> # Modul 4
Modul 4 ini berisi tentang Operator yaitu Operator adalah sebuah simbol. Simbol yang digunakan untuk melakukan
operasi tertentu. Misalnya: Kita ingin menjumlahkan nilai dari variabel x dan y, maka kita bisa menggunakan operator penjumlahan (+).
x + y

Modul 4_1
