 Assalamu'alaikm Warahmatullahi Wabarakatuh . . .
 Nama : Hasan Maulana.....  NIM : 311910167.... Kelas : TI.19.A.1
 
 Hasil Langkah-langkah Praktikum ke 2
 
 1. Membuat Dokumen HTML nya 
 ![1](https://user-images.githubusercontent.com/56497286/113879739-09a44e80-97e5-11eb-8ace-18c977014d57.png)
![2](https://user-images.githubusercontent.com/56497286/113879782-15901080-97e5-11eb-90c2-01c9d551d8e5.png)

dan hasilnya
![hasil 1 2](https://user-images.githubusercontent.com/56497286/113879848-23de2c80-97e5-11eb-89ad-b4f0f8062432.png)

2. Mendeklarasikan CSS internal
memasukan kode CSS di dalam head di bawah tittle (untuk memberikan format yang ada di dalam body, header, h1, h1 i).
![5](https://user-images.githubusercontent.com/56497286/113881690-d9f64600-97e6-11eb-96bf-7dfe36394df8.png)

3. Menambah inline CSS
Memasukan deklarasi inline di dalam paragraf tag "p".

4. Membuat CSS eksternal
membuat file baru css style_eksternal.css dan memasukan deklarasi css.
dan memasukan link ke dalam file html di dalam head untuk memanggil file css yang telah di buat.

5. Menambahkan CSS selector
Membuat CSS selectero yang di ambil dari file html sebelumnya yang sudah di beri id.

6. Hasil validasi CSS
![6](https://user-images.githubusercontent.com/56497286/113882938-ec24b400-97e7-11eb-9b8f-2b7611bb7fee.png)


Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!
4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

Jawaban :
1. input an nya ....
![a](https://user-images.githubusercontent.com/56497286/113883859-baf8b380-97e8-11eb-8da8-69f422755719.png)
![b](https://user-images.githubusercontent.com/56497286/113883929-cb109300-97e8-11eb-8c61-6f395cee55ca.png)
![c](https://user-images.githubusercontent.com/56497286/113884027-da8fdc00-97e8-11eb-9aea-44357a1f399c.png)
![d](https://user-images.githubusercontent.com/56497286/113884061-e2e81700-97e8-11eb-80e5-1f3aab7e51c4.png)

output nya
![output](https://user-images.githubusercontent.com/56497286/113884160-f6937d80-97e8-11eb-9b0b-1f557e8320d5.png)

2. elemen h1 biasanya ada di dalam css internal berbeda dengan #intro h1 dia menggunakan selector id didalam file html untuk di deklarasikan kedalam file css. Biasanya H1 hanya digunakan satu kali dalam sebuah halaman web, yaitu sebagai judul utama (judul besar), Sedangkan Intro di gunakan untuk memisahkan perintah dalam satu kesatuan

3. Bila CSS external di dalam internal masih bisa muncul di chrome tetapi bila ada CSS selector maka div harus di dalam "body", karena fungsi CSS eksternal adalah untuk Kecepatan loading menjadi lebih cepat dan File CSS yang sama bisa digunakan di banyak halaman. pada dasarnya hasilnya sama saja. Karena CSS eksternal digunakan untuk menggabungkan CSS ke website dengan menggabungkan file, dengan cara tersebut, perubahan apapun yang dibuat pada file CSS akan tampil pada website secara keseluruhan

![output](https://user-images.githubusercontent.com/56497286/113885053-b5e83400-97e9-11eb-8633-a438aef84dbf.png)
![c](https://user-images.githubusercontent.com/56497286/113885550-22633300-97ea-11eb-9ba0-0985f3a33c64.png)
![d](https://user-images.githubusercontent.com/56497286/113885605-2a22d780-97ea-11eb-8ac8-a978cfadf568.png)

4. Semuanya akan tampak. Namun Class mampu memanggil sekaligus atau berkali-kali pada satu halaman, sedangkan ID tidak bisa di panggil lebih dari satu..  Dua duanya akan di tampilkan, ID dengan deklarasi "#" Class dengan deklarasi "."
![123](https://user-images.githubusercontent.com/56497286/113886800-293e7580-97eb-11eb-861c-a3dd0e5476bb.png)
![456](https://user-images.githubusercontent.com/56497286/113886834-2e032980-97eb-11eb-9533-895160ca0c4a.png)

output nya
![789](https://user-images.githubusercontent.com/56497286/113886866-33f90a80-97eb-11eb-9195-68e9073eb459.png)



