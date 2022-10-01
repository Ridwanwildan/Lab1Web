# Latihan menggunakan tag HTML  

* Nama          : Hizbullah Ridwan
* NIM           : 312110055
* Kelas         : TI.21.B.1
* Mata Kuliah   : Pemrograman Web

Dalam latihan menggunakan tag HTML ini, saya menggunakan [Google Chrome](https://www.google.com/intl/id_id/chrome/) sebagai web browser dan [visual studio code](https://code.visualstudio.com/) sebagai teks editornya.       

Daftar isi :          
* [Tag Dasar](https://github.com/Ridwanwildan/Lab1Web#tag-dasar)         
* [Membuat Paragraf](https://github.com/Ridwanwildan/Lab1Web#membuat-paragraf)         
* [Menambahkan Judul](https://github.com/Ridwanwildan/Lab1Web#menambahkan-judul)                        
* [Memformat Teks](https://github.com/Ridwanwildan/Lab1Web#memformat-teks)                  
* [Menyisipkan Gambar](https://github.com/Ridwanwildan/Lab1Web#menyisipkan-gambar)                  
* [Menambahkan Hyperlink](https://github.com/Ridwanwildan/Lab1Web#menambahkan-hyperlink)                  

## Tag Dasar

Hal pertama yang harus dilakukan adalah membuat sebuah file baru dengan tipenya adalah HTML.            
Kemudian untuk membuat tag dasar contohnya adalah seperti ini :            

![Gambar 1](Screenshoots/Capture1.PNG)      

Setelah itu, buka file HTML tersebut di web browser. Bisa dengan menggunakan [Google Chrome](https://www.google.com/intl/id_id/chrome/), [Mozilla Firefox](https://www.mozilla.org/id/firefox/), [Opera](https://www.opera.com/), dan lainnya.          

![Gambar 2](Screenshoots/Capture2.PNG)                 

Halaman web masih terlihat kosong karena belum diisi tag apapun pada bagian `<body>`. Hanya terlihat title nya         
saja yang sudah diberi nama *Tag dasar HTML*.       

## Membuat Paragraf

Tag paragraf berfungsi untuk menambahkan teks atau paragraf di halaman website. Tag paragraf diawali           
dengan `<p>` dan diakhir harus ditutup dengan tag `</p>`. Seperti ini :        

![Gambar 3](Screenshoots/Capture3.PNG)                 

Kemudian refresh web browser yang tadi sudah membuka file HTML supaya perubahannya terlihat.            

![Gambar 4](Screenshoots/Capture4.PNG)             

Setiap paragraf bisa diatur posisinya seperti rata kiri, kanan, maupun tengah.      
Caranya adalah dengan menambahkan atribut pada tag paragrafnya. Seperti ini :        

![Gambar 5](Screenshoots/Capture5.PNG)             

Value pada atribut `align` juga bisa diubah menjadi `justify`, `right`, dan lainnya.         
Jangan lupa refresh untuk melihat hasilnya di web browser.          

![Gambar 6](Screenshoots/Capture6.PNG)             

Selain itu, paragraf juga bisa ditambahkan beberapa tag pendukung lainnya seperti         
tag `<hr/>` digunakan untuk menambahkan garis horizontal sebelum atau sesudah paragraf.       
tag `<br/>` digunakan untuk memisah paragraf ke baris berikutnya (ke baris bawah).       
tag `<pre>` digunakan untuk membuat spasi panjang pada paragraf.        

Seperti ini :           

![Gambar 16](Screenshoots/Capture16.PNG)             
![Gambar 17](Screenshoots/Capture17.PNG)             

## Menambahkan Judul

Menambahkan judul atau biasa disebut header teks bisa dilakukan dengan menambahkan tag `h` pada html.          
Ukuran header teks pada HTML bisa disesuaikan, ada header dengan ukuran 1 yang paling besar dan         
header ukuran 6 untuk ukuran teks yang paling kecil.           

```bash
<h1>header teks ukuran 1</h1>
<h2>header teks ukuran 2</h2>
<h3>header teks ukuran 3</h3>
<h4>header teks ukuran 4</h4>
<h5>header teks ukuran 5</h5>
<h6>header teks ukuran 6</h6>
```      

 ![Gambar 7](Screenshoots/Capture7.PNG)             

 Hasilnya akan seperti ini :              

 ![Gambar 8](Screenshoots/Capture8.PNG)             

 ## Memformat Teks

 Mengubah format pada teks disuatu paragraf menjadi italic, bold, underline, dan sebagainya bisa              
 dilakukan pada HTML.       
 Tag `<i>` digunakan untuk mengubah format teks menjadi miring.              
 Tag `<b>` digunakan untuk mengubah format teks menjadi tebal.          
 Tag `<u>` digunakan untuk mengubah format teks menjadi garis bawah.            
 Tag `<mark>` digunakan untuk mengubah format teks menjadi highlight/marking.        
 Tag `<sup>` digunakan untuk mengubah format teks menjadi superscript.         
 Tag `<sub>` digunakan untuk mengubah format teks menjadi subscript.              
 Tag `<del>` digunakan untuk mengubah format teks menjadi garis tengah.        

 Tag-tag tersebut bisa langsung disisipkan kedalam paragraf. Contohnya ini :        

 ![Gambar 9](Screenshoots/Capture9.PNG)             

 ![Gambar 10](Screenshoots/Capture10.PNG)             
 
 ## Menyisipkan Gambar

 Untuk menyisipkan gambar kedalam website, caranya adalah menggunakan tag `<img>`. Gambar yang             
 akan disisipkan kedalam website bisa disimpan di penyimpanan internal dan bisa juga diambil dari            
 web lain tanpa harus menyimpannya terlebih dahulu. Seperti ini :           

 ![Gambar 11](Screenshoots/Capture11.PNG)             

 ![Gambar 12](Screenshoots/Capture12.PNG)             

 Sedangkan cara untuk menyisipkan gambar dari web lain atau external link seperti ini :         

 ![Gambar 13](Screenshoots/Capture13.PNG)             

 Gambar yang muncul di website adalah ukuran gambar yang asli dan tidak ada perubahan.         
 Untuk mengatur ukuran gambar bisa tambahkan atribut `width` untuk mengatur lebar gambar            
 dan `height` untuk mengatur tinggi gambar. Sisipkan atribut `width` dan `height` pada tag `<img>`.           
 Sedangkan untuk gambar yang ukuran antara lebar dan tingginya ingin disamakan, maka          
 cukup gunakan atribut `width` saja.          

 Atribut `title` yang ada didalam tag `<img>` fungsinya adalah memberikan judul pada gambar tersebut.       

 ## Menambahkan Hyperlink

 Hyperlink atau link navigasi bisa ditambahkan kedalam HTML dengan cara menggunakan tag `<a>` dan         
 ditambah dengan atribut `href`. Sama seperti menambahkan gambar, hyperlink bisa diambil dari          
 file internal dan bisa juga dari link external. Seperti ini :          

![Gambar 14](Screenshoots/Capture14.PNG)             

![Gambar 15](Screenshoots/Capture15.PNG)             