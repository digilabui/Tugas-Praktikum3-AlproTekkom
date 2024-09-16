# Tugas Praktikum Modul 3

Nama : [Change Me]

NPM : [Change Me]

# Soal Teori

## 1. Jelaskan yang dimaksud dengan Sorting. Jelaskan kapan sorting perlu dilakukan! (20 poin)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non curabitur gravida arcu ac tortor. Dapibus ultrices in iaculis nunc sed augue. Orci ac auctor augue mauris augue neque. Dictumst vestibulum rhoncus est pellentesque elit. In ornare quam viverra orci. Purus semper eget duis at tellus at urna condimentum. Vitae justo eget magna fermentum iaculis eu. Venenatis a condimentum vitae sapien pellentesque. Faucibus scelerisque eleifend donec pretium vulputate. Nisl pretium fusce id velit ut tortor pretium viverra suspendisse. Vitae sapien pellentesque habitant morbi tristique senectus.

### Referensi :

## 2. Jelaskan yang dimaksud dengan inplace sorting dan stable sorting (20 poin)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non curabitur gravida arcu ac tortor. Dapibus ultrices in iaculis nunc sed augue. Orci ac auctor augue mauris augue neque. Dictumst vestibulum rhoncus est pellentesque elit. In ornare quam viverra orci. Purus semper eget duis at tellus at urna condimentum. Vitae justo eget magna fermentum iaculis eu. Venenatis a condimentum vitae sapien pellentesque. Faucibus scelerisque eleifend donec pretium vulputate. Nisl pretium fusce id velit ut tortor pretium viverra suspendisse. Vitae sapien pellentesque habitant morbi tristique senectus.

### Referensi :

## 3. Perhatikan ilustrasi algoritma sorting berikut (25 poin)

![Sorting](https://cdn.digilabdte.com/u/suK31o.png)

Algoritma sorting apa yang digunakan pada ilustrasi tersebut? Jelaskan cara kerjanya!

## 4. Adakah jenis algoritma sorting yang memanfaatkan rekursi? Jelaskan kelebihan dan kekurangan dari algoritma tersebut (20 poin):

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non curabitur gravida arcu ac tortor. Dapibus ultrices in iaculis nunc sed augue. Orci ac auctor augue mauris augue neque. Dictumst vestibulum rhoncus est pellentesque elit. In ornare quam viverra orci. Purus semper eget duis at tellus at urna condimentum. Vitae justo eget magna fermentum iaculis eu. Venenatis a condimentum vitae sapien pellentesque. Faucibus scelerisque eleifend donec pretium vulputate. Nisl pretium fusce id velit ut tortor pretium viverra suspendisse. Vitae sapien pellentesque habitant morbi tristique senectu.

## 5. Menurut anda, sorting algorithm apa yang paling mudah untuk digunakan? Jelaskan alasan anda menyebutkan sorting algorithm tersebut (15 poin)

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non curabitur gravida arcu ac tortor. Dapibus ultrices in iaculis nunc sed augue. Orci ac auctor augue mauris augue neque. Dictumst vestibulum rhoncus est pellentesque elit. In ornare quam viverra orci. Purus semper eget duis at tellus at urna condimentum. Vitae justo eget magna fermentum iaculis eu. Venenatis a condimentum vitae sapien pellentesque. Faucibus scelerisque eleifend donec pretium vulputate. Nisl pretium fusce id velit ut tortor pretium viverra suspendisse. Vitae sapien pellentesque habitant morbi tristique senectus.


# Soal Pemrograman

## 1. Buatlah sebuah program dalam bahasa C untuk mengurutkan bilangan secara descending. (30 poin)

Algoritma yang anda gunakan untuk melakukan sorting dibebaskan.
Contoh input: 68, 7, 25, 31, 92, 175
Output: 175, 92, 68, 31, 25, 7 (Terurut secara descending)

### Video: Jelaskan cara kerja sorting algorithm yang anda digunakan? Apakah anda menggunakan function swap dalam program? Jelaskan kegunaan function swap tersebut!

## 2. Sorting Data Pelajar (70 poin)

Suatu hari, Professor Azar dari Akademiya meminta anda sebagai programmer untuk membantu permasalahan data. Akademiya memiliki banyak pelajar dan dibutuhkan sebuah sistem pengurutan data pelajar. Oleh karena itu, Professor Azar meminta anda untuk membuat program mengurutkan data pelajar Darshan Amurta (Fakultas Biologi) di Akademiya. Berikut
ketentuannya:
- Program dapat menyimpan input N banyaknya data pelajar dengan isi NAMA, NPM, dan IPK. (Gunakan struct!)
- Program akan mengurutkan nama pelajar dari N banyaknya pelajar diurutkan berdasarkan alfabet
- Program harus mengimplementasikan modular programming, dengan membuat minimal 1 buah fungsi, yaitu fungsi untuk mengurutkan karakter.
- Program diperkenankan untuk menggunakan library string.h
- Program harus diselesaikan dengan menggunakan algoritma sorting
Bantulah Professor Azar untuk membuat program tersebut!
Input
Bilangan bulat N (jumlah pelajar), dan data pelajar (NAMA, NPM, IPK).
Output
Print N data pelajar (data NAMA, NPM, IPK) secara berurutan berdasarkan nama pelajar.
![epic](https://cdn.digilabdte.com/u/UljFnI.jpg)

Testcase:
```c
5
Albedo
2106655034
4.0
Ganyu
2002123020
3.9
Jean
1900122310
3.5
Venti
2106651234
3.7
Aldrian
2106653256
3.0
```

### Video: Jelaskan secara keseluruhan kode yang anda telah buat. Dalam melakukan sorting, jelaskan cara anda membandingkan 2 string. Dalam sorting apakah Uppercase dan lowercase string memiliki nilai yang sama? Jelaskan cara agar sorting dapat dilakukan dengan atau tanpa membandingkan uppercase / lowercase dari string.