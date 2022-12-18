# Pertemuan.13_Praktikum.9

## Repository ini dibuat untuk memenuhi tugas mata kuliah Bahasa Pemrograman.

## Nama   : Aditia Seftiawan

## NIM    : 312210094

## Kelas  : TI.22.B1

## Berikut ini adalah contoh dan penjelasan modul Praktikum 13.


1. Berikut adalah fungsi yang mengubah suhu dari derajat derajat Kelvin menjadi derajat Fahrenheit. Karena nol derajat derajat Kelvin sedingin yang didapat, fungsi tersebut ditebus jika melihat suhu negatif.

![exception](https://user-images.githubusercontent.com/115516473/208232159-2b286b13-53a9-4d40-b83e-efa40f909c42.png)

Ketika kode di atas dijalankan, muncul Exception yang bernama Traceback... `AssertionError` artinya terjadi error pada pernyataan assert.

2. Berikut ini adalah Contoh untuk membuka file, menulis konten di file dan keluar dengan lancar karena tidak ada masalah sama sekali.

![prak 9](https://user-images.githubusercontent.com/115516473/208232774-4146e137-d051-47c8-8432-8e1f8936e12a.png)

Hasilnya seperti berikut ini:

```
Written content in the file successfully
```

Hasilnya seperti ini karena else akan dijalankan ketika try adalah True

3. Contoh ini mencoba membuka file di mana Anda tidak memiliki izin menulis, sehingga menimbulkan pengecualian.

![prak 9-2](https://user-images.githubusercontent.com/115516473/208233322-41ef7a58-a485-4632-99a5-29a10950fae6.png)

Mengapa hasilnya error? 

r adalah read - Membuka file untuk membaca, akan error jika file tidak ada. Disini ingin membaca file bukan menulis maka dibawahnya ```fh = open("testfile", "r")``` tambahkan ```print(fh.readline())``` dan fh.write dihapus. Setelah dijalankan, try dan else ditampilkan.

4. Berikut ini adalah contoh keempat 

![prak 9-3](https://user-images.githubusercontent.com/115516473/208242848-5e8f3f5d-5a07-4bb7-81c2-c211f3c23da0.png)

Hasil diatas bukan error, karena finally dijalankan ketika try dan except dijalankan. Dan berhasil dibuat filenya setelah dijalankan.

5. Berikut ini adalah Contoh single exception

![prak 9-4](https://user-images.githubusercontent.com/115516473/208243105-f48bd09a-f68c-4cda-ad11-64b3b7b4950b.png)

Hasilnya seperti berikut ini : 

```
The argument does not contain numbers 
invalid literal for int() with base 10: 'xyz'
```

ketika dijalankan, maka muncul error. Hapus ```#!/usr/bin/python``` dan di ```except ValueError, Argument:``` ganti koma dengan as seperti ```except ValueError as Argument:```agar tidak error. Jika dijalankan akan muncul error lagi. Kenapa? karena parameter def temp_convert harus mengandung angka.

6. Berikut Contoh dan penjelasan keenam

![prak 9-5](https://user-images.githubusercontent.com/115516473/208243725-a8418191-cedb-436b-8719-2c4d27a95c3a.png)

Jika dijalankan muncul SyntaxError artinya ada kesalahan sintaks. Pada raise ```"Invalid level!", level``` ganti tanda koma dengan tanda plus. Cetak def dengan angka yang lebih besar dari 1.

### Selesai

### Demikianlah sedikit penjelasan dari saya, kurang lebihnya mohon maaf.

## Terimakasih








