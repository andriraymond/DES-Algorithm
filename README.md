# DES-Algorithm

* Felix Giovanni Virgo
* 14/365960/PA/16167

## Overview

DES (Data Encryption Standard) adalah algoritma cipher blok yang populer karena dijadikan standard algoritma enkripsi kunci-simetri, meskipun saat ini standard tersebut telah digantikan dengan algoritma yang baru, AES, karena DES sudah dianggap tidak aman lagi. Sebenarnya DES adalah nama standard enkripsi simetri, nama algoritma enkripsinya sendiri adalah DEA (Data Encryption Algorithm). DES termasuk ke dalam sistem kriptografi simetri dan tergolong jenis cipher blok. DES beroperasi pada ukuran blok 64 bit. DES mengenkripsikan 64 bit plainteks menjadi 64 bit cipherteks dengan menggunakan 56 bit kunci internal (internal key). Kunci internal dibangkitkan dari kunci eksternal (external key) yang panjangnya 64 bit.

## Dokumentasi

Source code ([DES.cpp](https://github.com/felixgiov/DES-Algorithm/blob/master/DES.cpp)) telah memuat dokumentasi mengenai kode beserta penjelasannya dalam bentuk comment. Pada setiap comment terdapat penjelasan 
Program ini berjalan di `main` function dan memuat beberapa step seperti yang diperlihatkan di bawah.

```sh
int main(){
  //Step 1. Permutasi PC1 pada Key
  //Step 2. Membuat Key C0 dan D0 hingga C16 dan D16
  //Step 3. Permutasi PC2 pada Key
  //Step 4. Permutasi IP pada Plain Text
  //Step 5. Generate R0/L0 to R16/L16
  //Expansion Table
  //Subtitution
  //Permutation Table
  //Permutasi Inverse IP
}
```

## Kontribusi
