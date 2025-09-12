# Tugas Asistensi P1 dan Overview 
### Mohammad Khirz El jausyan
Tugas Asistensi dan overview P1-Praktikum Dasar Pemrograman 

<mark>Overview, kilas balik</mark>
## Basic C programming
1. Struktur utama Bahasa C
2. Membuat operasi matematika sederhana

sebelumnya kita sudah belajar mengenai dasar pemrograman bahasa C, kita belajar bagaimana cara mencetak kalimat di komputer, nah sebelum itu aku mau ngasih cheatsheet ke temen-temen
cara memahami bahasa C dengan mudah. jadi temen2 bahasa C itu punya struktur utama sebagai berikut

```sh
#include <stdio.h>

// kamu bisa kasih fungsi sembarang disini

int main() {
    // Kamu bisa kasih code sembarang disini
    return 0;
}
```
code diatas merupakan struktur utama bahasa C, mau seberapa panjang codenya mau seberapa kompleks pasti strukturnya sama kayak gitu, jadi next kalau temen2 coding C pertama kali tuli itu dulu ya..
yuk kita breakdown satu satu
1. kita panggi library 
   
Dalam pemrograman, kita sering membutuhkan alat atau fungsi yang sudah dibuat orang lain. Di C, "alat-alat" ini disimpan dalam file yang disebut library (pustaka). Untuk menggunakannya, kita perlu memasukkannya ke dalam program kita dengan perintah analoginya kita mau menulis dasar teori laporan praktikum nah sitasi dan teorinya ada di buku, kita perlu ambil buku dan lihat sitasinya, sama kayak program C kalau kita mau lakuin sesuatu contohnya print kata-kata, kita perlu panggil compiler yang bisa cetakk kata-kata, buat panggil library pakai sintaks ini
  ```sh
  #inlude <stdio.h>
  ```

2. Buat fungsi utama
   
fungsi utama adalah bagian dimana code utamamu dieksekusi. Setiap program C harus memiliki satu fungsi utama yang disebut main. Fungsi ini adalah titik awal program Anda. Apa pun yang ingin Anda     jalankan akan dimulai dari dalam fungsi main.

Struktur dasarnya terlihat seperti ini:
```sh
int main() {
    // Kamu bisa kasih code sembarang disini
    return 0;
}
```
3. Membuat Operasi matematika sederhana
   oke Mari kita terapkan konsep di atas untuk membuat program yang menghitung luas persegi. Rumus luas persegi adalah: luas = sisi x sisi
   ```sh
   #include <stdio.h>

    int main() {
        // Definisikan variabel untuk menyimpan nilai
        int sisi = 5;
        int luas;

        // Lakukan operasi matematika
        luas = sisi * sisi;

        // Cetak hasilnya ke layar
        printf("Sisi persegi adalah: %d\n", sisi);
        printf("Jadi, luas persegi adalah: %d\n", luas);

        return 0;
    }
   ```
# Tugas Asistensi
1. Perbaiki code dibawah ini:
   
   hint:
   - cek struktur utama code C
   ```sh
   #include <stdio.h>

    int main() {
        return 0;
        printf("in Engineering ITS we trust!\n");
    }
   ```
2. buat code utuk menghitung volume kubus:

   hint:
   - cari rumus menghitung volume kubus
   - kubus sama dengan persegi dalam 3D
   - tinggal tambahin dikit code menghitung luas persegi

codenya tulis ulang di komputer yaa.. boleh coding di codeblocks, di vscode, atau di notepad, atau kalau temen2 ngga punya aplikasi coding bisa coding di [situs ini](https://www.onlinegdb.com/online_c_compiler)  itu situs buat coding online, nah nanti run codenya dan di screenshoot dan disimpan dengan format <mark>soal-1/2_Nama_NRP</mark> kalau sudah temen2 bisa buat folder gdrive dan upload tugas ke gdrive, masing masing pserta buat folder baru ya.. kasih nama foldernya nama temen-temen yaa..
