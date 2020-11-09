# Lab 3
## Latihan 1
- Buat program dengan perulangan bertingkat (nested) for yang menghasilkan output sebagai berikut:

![PY3](https://user-images.githubusercontent.com/73066008/98462237-4b54ad00-21e5-11eb-86eb-f18390b2c0e7.jpg)

Input :

![Screenshot (58)](https://user-images.githubusercontent.com/73066008/98462418-edc16000-21e6-11eb-9577-02c12bae245f.png)

Penjelasan :

- for row in range(0, 10): dan for col in range(0, 10): untuk membuat list antara 0 sampai 10
- num = row + col nilai row dan col akan di tampung di variabel num
- if num < 10: jika num lebh kecil dari 10 maka empty = " "
- else: selain itu jika if num < 100: maka empty = " "
- dan cetak print(empty, num, end = '') print()

Output :

![Screenshot (59)](https://user-images.githubusercontent.com/73066008/98462422-f74ac800-21e6-11eb-8d30-024d0536e9c6.png)

## Latihan 2

![lat2](https://user-images.githubusercontent.com/73066008/98462577-d3d44d00-21e7-11eb-9e5c-9abcca889e23.jpg)

Input :

![Screenshot (64)](https://user-images.githubusercontent.com/73066008/98462688-b2279580-21e8-11eb-99f5-b89d628114d2.png)

Penjelasan :

- import random berfungsi untuk memanggil library random, dimana random berfungsi untuk menentukan pilihan secara acak
- nilai = int(input('Masukan nilai n : ')) untuk menginputkan nilai berupa integer
- range() berfungsi menghasilkan list
- masukkan i = random.uniform (.0,.5) di gunakan untuk menampilkan bilangan float random, lalu masukkan a+=1 untuk memberi nomer pada bilangan float.
- print('data ke :',a,'==>', i) untuk menampilkan output data

Output:

![Screenshot (65)](https://user-images.githubusercontent.com/73066008/98462696-b81d7680-21e8-11eb-83f0-a1b1a103b76e.png)

# Modul Praktikum 2
## Latihan 1 : Membuat program menentukan nilai akhir

Input :

![Screenshot (68)](https://user-images.githubusercontent.com/73066008/98462917-4f36fe00-21ea-11eb-8714-2bf7580cb044.png)

Penjelasan :

- Masukkan nilai yang sudah di tentukan oleh variabel, seperti nama, uts, uas,tugas
- untuk akhir = (int(tugas) * .2) + (int(uts) * .4) + (int(uts) * .4)
- if akhir > 80: Jika nilai akhir diatas 80, maka huruf = 'A'
- elif akhir > 70: dan jika nilai akhir diatas 70, maka huruf = 'B'
- elif akhir > 50: dan jika nilai akhir diatas 50, maka huruf = 'C'
- elif akhir > 40: dan jika nilai akhir diatas 40, maka huruf = 'D'
- else: selain itu maka huruf = 'E'
- cetak nilai akhir print 

Output :

![Screenshot (69)](https://user-images.githubusercontent.com/73066008/98462922-53fbb200-21ea-11eb-9615-3c7c8e7a004c.png)

## Latihan 2: Membuat program menampilkan status gaji karyawan

Input :

![Screenshot (72)](https://user-images.githubusercontent.com/73066008/98463207-39c2d380-21ec-11eb-931e-e2182d4970c6.png)

Penjelasan :

- gaji = int(input("Masukkan gaji:")) masukkan jumlah gaji
- if gaji > 3000000: jika gaji diatas 3jt, maka print ("Gaji sudah diatas UMR") jika tidak, maka else: print("Gaji belum UMR") dan juga pengkondisian yang lainnya
- maka data akan di cetak sesuai data yang di isi 

Output :

![Screenshot (73)](https://user-images.githubusercontent.com/73066008/98463213-3e878780-21ec-11eb-9d7d-5fbb223c3367.png)

## Latihan 3: penggunaan kondisi OR program membandingkan 3 input bilangan, apabila penjumlahan 2 bilangan hasilnya sama dengan bilangan lainnya, maka cetak pernyataan “BENAR”

Input :

![Screenshot (76)](https://user-images.githubusercontent.com/73066008/98464778-9aa3d900-21f7-11eb-977a-b9ab1f647992.png)

Penjelasan :

- a = int(input('Masukkan bilangan A: ')) Masukkan bilangan A pada saat runtime, lakukan juga pada bilangan B dan C
- if a+b == c or b+c == a or c+a == b: jika a+b = c atau b+c = a atau c+a = b maka print('benar')
- selain itu maka else: print('salah')

Output jika benar :

![Screenshot (77)](https://user-images.githubusercontent.com/73066008/98464782-a2637d80-21f7-11eb-850e-934cf9083cae.png)

jika salah :

![Screenshot (78)](https://user-images.githubusercontent.com/73066008/98464789-a98a8b80-21f7-11eb-92e6-964c51afc6db.png)

## Tugas praktikum 2

![Screenshot (80)](https://user-images.githubusercontent.com/73066008/98465261-a218b180-21fa-11eb-8cf3-d446cd250750.png)

Input :

![Screenshot (82)](https://user-images.githubusercontent.com/73066008/98465400-692d0c80-21fb-11eb-8e20-1bb47079bbb4.png)

Penjelasan :

- A = int(input('Masukkan bilangan pertama: ')) masukkan nilai bilangan pertama, dan lakukan juga pada bilangan kedua dan ketiga pada saat runtime
- if A > B and A > C: jika A lebih besar dari B dan A lebih besar dari C maka print('Nilai', A, 'terbesar dari 3 bilangan yang di inputkan')
- elif B > A and B > C: dan jika B lebih besar dari A dan B lebih besar dari C maka print('Nilai', B, 'terbesar dari 3 bilangan yang di inputkan')
- else: selain itu maka print('Nilai', C, 'terbesar dari 3 bilangan yang di inputkan')

Output :

![Screenshot (83)](https://user-images.githubusercontent.com/73066008/98465409-6df1c080-21fb-11eb-952c-a8c21066d4eb.png)

Flowchart :

![0001 (2)](https://user-images.githubusercontent.com/73066008/98469376-bc11be80-2211-11eb-9271-e238fa59f601.jpg)

# Modul praktikum 3
## Latihan 1

![Screenshot (86)](https://user-images.githubusercontent.com/73066008/98486522-4d078a80-2250-11eb-990a-92a19caa6528.png)

Input :

![Screenshot (64)](https://user-images.githubusercontent.com/73066008/98462688-b2279580-21e8-11eb-99f5-b89d628114d2.png)

Penjelasan :

- import random berfungsi untuk memanggil library random, dimana random berfungsi untuk menentukan pilihan secara acak
- nilai = int(input('Masukan nilai n : ')) untuk menginputkan nilai berupa integer
- range() berfungsi menghasilkan list
- masukkan i = random.uniform (.0,.5) di gunakan untuk menampilkan bilangan float random, lalu masukkan a+=1 untuk memberi nomer pada bilangan float.
- print('data ke :',a,'==>', i) untuk menampilkan output data

Output :

![Screenshot (65)](https://user-images.githubusercontent.com/73066008/98462696-b81d7680-21e8-11eb-83f0-a1b1a103b76e.png)

## Latihan 2

![Screenshot (91)](https://user-images.githubusercontent.com/73066008/98487142-1895cd80-2254-11eb-9859-242ad2aa69e7.png)

Input :

![Screenshot (99)](https://user-images.githubusercontent.com/73066008/98492024-315cae00-2269-11eb-96da-50ce662ea425.png)

Penjelasan :

- Integer max = 0
- fungsi perulangan while true hingga menampilkan perulangan sampai batas tertentu.
- Memasukan bilangan integer pada "a"
- Menggunakan fungsi if jika max kurang dari nilai a, maka max sama dengan a
- Mengunakan fungsi if jika nilai a adalah 0 maka fungsi break artinya perulangan berhenti jika menulis nilai 0
- Mencetak nilai paling terbesar setelah break, sehingga menampilkan nilai terbesar diantara bilangan tersebut dalam perulangan.

Output :

![Screenshot (100)](https://user-images.githubusercontent.com/73066008/98492034-3883bc00-2269-11eb-9bd2-7f5543a4b568.png)


## Tugas praktikum 3

![Screenshot (94)](https://user-images.githubusercontent.com/73066008/98487829-f3a35980-2257-11eb-8d45-d1a1318dfa51.png)

Input :

![Screenshot (95)](https://user-images.githubusercontent.com/73066008/98488040-72e55d00-2259-11eb-9ceb-01a452149aee.png)

Penjelasan :

- Variabel a = 100.000.000 modal awal
- Menggunakan fungsi looping for pada nilai x 1-9 untuk menampilkan bulan 1 sampai bulan 8.
- Menggunakan fungsi if, untuk menghitung laba bulan 1 sampai 8
- Bulan pertama dan kedua laba adalah 0
- Bulan ke 3 dan ke 4 mendapat laba 1% sehingga modal di kali 1% = keuntungan
- Bulan ke 5 mendapatkan laba 5%, sehingga modal dikali 5% = keuntungan
- Bulan ke 8 mendapatkan laba 2% sehingga keuntungan menurun dari bulan sebelumnya, modal dikali 2% = keuntungan.
- Menghitung jumlah total laba dengan menjumlah keuntungan dari bulan ke 1 sampai bulan 8, hasilnya adalah total keuntungan yang didapat total=b+b+c+c+d+d+d+e
- print("\Total : ",total), untuk menampilkan hasil keseluruhan laba dari bulan pertama sampai bulan kedelapan.

Output :

![Screenshot (96)](https://user-images.githubusercontent.com/73066008/98488050-84c70000-2259-11eb-8499-41b63b22a0a5.png)

Flowchart :

![0001](https://user-images.githubusercontent.com/73066008/98489980-b42e3a80-2262-11eb-9d9c-61c5f1b7bca3.jpg)