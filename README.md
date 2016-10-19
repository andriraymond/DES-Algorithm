# DES-Algorithm

* Felix Giovanni Virgo
* 14/365960/PA/16167

### Anggota Kelompok

* Ferdinand Winstein
* Felix Giovanni Virgo
* Mochamad Gading Prabowo
* Nikolaus Aldo
* Vido Valianto
* Wibisana Wiratama

## Overview

DES (Data Encryption Standard) adalah algoritma cipher blok yang populer karena dijadikan standard algoritma enkripsi kunci-simetri, meskipun saat ini standard tersebut telah digantikan dengan algoritma yang baru, AES, karena DES sudah dianggap tidak aman lagi. Sebenarnya DES adalah nama standard enkripsi simetri, nama algoritma enkripsinya sendiri adalah DEA (Data Encryption Algorithm). DES termasuk ke dalam sistem kriptografi simetri dan tergolong jenis cipher blok. DES beroperasi pada ukuran blok 64 bit. DES mengenkripsikan 64 bit plainteks menjadi 64 bit cipherteks dengan menggunakan 56 bit kunci internal (internal key). Kunci internal dibangkitkan dari kunci eksternal (external key) yang panjangnya 64 bit.

## Dokumentasi

Source code ([DES.cpp](https://github.com/felixgiov/DES-Algorithm/blob/master/DES.cpp)) telah memuat dokumentasi mengenai kode beserta penjelasannya dalam bentuk comment. Untuk melihat dokumentasi kode, dapat dilihat langsung di source code ([DES.cpp](https://github.com/felixgiov/DES-Algorithm/blob/master/DES.cpp)). Semua proses terjadi secara prosedural. Program ini berjalan di `main` function dan memuat beberapa step seperti yang diperlihatkan di bawah. 

```cpp
int main(){
  //Permutasi PC1 pada Key
  //Membuat Key C0 dan D0 hingga C16 dan D16
  //Permutasi PC2 pada Key
  //Permutasi IP pada Plain Text
  //Generate R0/L0 to R16/L16
  //Expansion Table
  //Subtitution
  //Permutation Table
  //Permutasi Inverse IP
}
```

### Referensi

http://page.math.tu-berlin.de/~kant/teaching/hess/krypto-ws2006/des.htm

## Kontribusi

Kontribusi saya dalam kelompok ini:

* Mengassist programmer utama (Ferdinand). 
* Membantu menulis beberapa baris kode `Expansion` dan melanjutkan program dari `SBOX` menjadi `Cipher Text`
* Membantu menjelaskan kepada anggota tim mengenai beberapa proses dalam algoritma DES.
* Ikut presentasi di kelas.
