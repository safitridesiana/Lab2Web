# Lab2Web
Belajar CSS

Nama : Desiana Eka Safitri
NIM : 311910738 
Kelas : TI19B1 
Prodi : Teknik Informatika 
Mata Kuliah : Pemrograman Web 
Dosen Pengajar : Agung Nugroho, S. Kom., M. Kom

Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS
dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

![Screenshot (145)](https://user-images.githubusercontent.com/81596251/113496682-53134600-9526-11eb-92d4-98c8569e1ccf.png)

Berikut kode yang ditambahkan dan diubah pada eksperimen:

Penambahan pada HTML
![Screenshot (147)](https://user-images.githubusercontent.com/81596251/113496831-d4b7a380-9527-11eb-894e-e1e7be07dd0a.png)

![image](https://user-images.githubusercontent.com/81596251/113496892-5d364400-9528-11eb-9a21-9f0bb98303e9.png)

Penambahan pada CSS
![Screenshot (151)](https://user-images.githubusercontent.com/81596251/113497028-cd919500-9529-11eb-91b8-b5b15c6246cf.png)

Tampilannya menjadi:
![Screenshot (149)](https://user-images.githubusercontent.com/81596251/113496937-ed748900-9528-11eb-9098-4c960c77ecbf.png)

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan
penjelasannya!

Elemen h1 {...}

![image](https://user-images.githubusercontent.com/81596251/113497158-54933d00-952b-11eb-892e-b2c2f49b4875.png)

Elemen h1 {...} yang dideklarasikan pada CSS mengacu pada style atau gaya teks saja yang ada di halaman awal web (sebagai header) atau memberi style CSS pada elemen HTML yang diingikan. Elemen h1 {...} mengacu pada Internal CSS yaitu menyisipkan CSS pada file HTML.

Elemen #intro h1 {...}
![image](https://user-images.githubusercontent.com/81596251/113497496-ff592a80-952e-11eb-87d1-43838a3eef9b.png)
![image](https://user-images.githubusercontent.com/81596251/113497397-ea2fcc00-952d-11eb-8f0b-1f3ca0d5ab0a.png)

Elemen #intro h1 {...} memiliki id maka penggunaan pada css dengan pagar (#) dan di dalam file index.html dalam pemanggilannya menggunakan id=" ". Elemen tersebut mengacu pada tampilan selector yang terdiri dari ID dan Class dimana ID selector ditandai dengan tanda pagar (#) di depannya.

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

Kode CSS internal diletakkan di dalam bagian <head> pada halaman. Class dan ID bisa digunakan untuk merujuk pada kode CSS, namun hanya akan aktif pada halaman tersebut (hanya 1 halaman). CSS internal diletakkan di dalam tag <style></style>.

![image](https://user-images.githubusercontent.com/81596251/113497972-d89cf300-9532-11eb-8358-2e6c1b1f115c.png)

Dengan menambahkan CSS eksternal, perubahan apapun yang kita buat pada file CSS akan tampil pada website kita secara keseluruhan. File CSS eksternal biasanya diletakkan setelah bagian <head> pada halaman.
![image](https://user-images.githubusercontent.com/81596251/113498042-8d371480-9533-11eb-87d8-fdbb4e309d4f.png)
![image](https://user-images.githubusercontent.com/81596251/113498051-acce3d00-9533-11eb-9679-854fc12bfeb1.png)

Kode Inline CSS ditulis langsung pada atribut elemen HTML. Setiap elemen HTML memiliki atribut style, di situ lah inline CSS ditulis.
![image](https://user-images.githubusercontent.com/81596251/113498107-2a924880-9534-11eb-8f43-472bebadf8a9.png)

Jadi, deklarasi yang akan tampil pada browser adalah semua dari ketiga deklarasi tersebut jika penggunaan dan penginputan ketika melakukan coding benar sesuai dengan peruntukkannya dan tidak ada error pada browser.

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
Berikan penjelasan dan contohnya! ( <p id="paragraf-1" class="text-paragraf"> )
Contoh:
![image](https://user-images.githubusercontent.com/81596251/113498313-f455c880-9535-11eb-92e8-a860f6de44b0.png)

Yang akan tampil pada browser:
![image](https://user-images.githubusercontent.com/81596251/113498322-14858780-9536-11eb-8687-4078de84d738.png)

 Jika kita meng-klik button "Informasi selengkapnya", maka akan muncul tampilan pada halaman yang sama karena pada elemen HTML terdapat pemanggilan "intro".
 ![image](https://user-images.githubusercontent.com/81596251/113498444-2287d800-9537-11eb-9ee0-7ac61349149c.png)

