#JAVASCRIPT

##Pengantar
Repo ini dibuat sebagai rangkuman belajar saya tentang JavaScript, dan membagikan hasil yang saya pelajari sebagai bentuk upaya berkonstribusi di dunia programming serta membalas jasa perjuangan-perjuangan para master programmer di dunia yang sudah dengan baik dan tulus meluangkan waktu membagikan ilmu dan membuatkan tutorial tentang programming sehingga sudah ada jutaan tutorial dan konten yang sangat berguna tersebar di internet.

------------
##Kenapa Belajar JavaScript?

Berikut pendapat-pendapat kenapa harus belajar javascript.
https://www.quora.com/Why-is-learning-JavaScript-programming-language-important-for-web-developers

------------



###note:
- repo ini akan selalu di update baik sisi README.md dan source code nya.
- setiap file, akan ada penjelasannya di bawah ini.

------------

##001.helloworld.html
```html
<html>
  <head>
    <meta charset="utf-8">
    <title>Belajar JavaScript</title>
  </head>
  <body>
    <script>
      alert("Helloworld");
    </script>
  </body>
</html>
```
Seperti biasa, hal pertama yang dilakukan dalam mempelajari sebuah pemograman adalah ritual Helloworld, dan code di atas adalah contoh hellowolrd pada Java Script.

Jika code di atas di jalankan, maka akan muncul tampilan pop up di browser dengan tulisan "Helloworld", kode java script di awali dengan tag ```<script> ``` dan di akhiri ```</script>```, jadi dapat disimpulkan bahwa kode javascript yang ada di atas adalah ```alert("Helloworld);```, ini merupakan sebuah function bernama alert() yang berguna untuk menampilkan pop up pada browser.

Tidak usah di pusingkan dulu tentang syntax nya, yang penting bisa menampilkan tulisan hellowolrd menggunakan javascript dan membedakan mana code javascript mana code html.
Selanjutnya kita coba belajar memasukan kode javascript kedalam html dengan 3 metode, yaitu inline, internal dan eksternal.

------------

##002.input-js-ke-html-inline.html

```javascript
<html>
  <head>
    <meta charset="utf-8">
    <title>Belajar JS</title>
  </head>
  <body>

    <button onclick="alert('Hellowolrd lagi broh..');">
      Klik disini.
    </button>

  </body>
</html>

```

Inline JavaScript, adalah cara memasukan kode java script ke html dengan menempatkan
kode javascript ke dalam attribut tag. Kode di atas adalah memasukan kode javascript ke dalam attribut tag "button"```<button code-javascript> ```.

Keyword onclick pada baris 8 adalah attribut khusus, atau sering di sebut event.
Event onclick ini berfungsi menjalankan kode javascript hanya pada saat tombol di klik.

Pointnya, dapat memahami dan mengerti cara memasukan kode javascript ke dalam tag html.
Jika masih belum mengerti, mungkin bisa di review lagi apa itu tag html, dan apa itu attribut. :D

------------

##003.input-js-ke-html-internal.html

```html
<html>
  <head>
    <meta charset="utf-8">
    <title>Belajar JS</title>
  </head>
  <script>
    alert("Alert Pertama");
  </script>
  <body>
    <h1>AAAAAAA</h1>

    <script>
      alert('Alert Kedua');
    </script>
    <h1>BBBBBBB</h1>

    <script>
      alert('Alert Ketiga');
    </script>
  </body>
</html>


```


Internal Javascript adalah, cara memasukan kode javascript ke dalam html dengan menggunakan tag ```<script> </script>```

Pada latihan Helloworld di file 001 adalah contoh memasukan kode java script ke html dengan metode Internal. Pada saat menjalankan kode diatas, maka kita bisa ber asumsi bahwa javascript ini di proses dari atas ke bawah.

Point, mengerti dan memahami apa itu metode internal javascript, dan bisa membedakan internal dengan inline.

------------

##004.input-js-ke-html-eksternal.html

Jika kita sudah paham atau sudah pernah belajar CSS, maka tidak akan asing dengan 3 metode ini, termasuk metode eksternal ini.
Dimana source code javascript dan source code html dipisahkan dengan dua file yang berbeda. Perhatikan contoh dibawah ini,

```html
<html>
  <head>
    <meta charset="utf-8">
    <title>Belajar JS</title>
  </head>
  <body>
    <h1>Latihan terus</h1>
    <script src="004.kode.js"></script>
  </body>
</html>
```

Kode di atas, disimpan sebagai file dengan nama 004.input-js-ke-html-eksternal.html yang berisikan code-code html to'(html doang/html saja).
Perhatikan kode ```<script src="004.kode.js"></script>``` , berfungsi memanggil code javascript yang disimpan dengan file bernama 004.kode.js, berikut isi file nya:
```javascript
alert('Hi ini dari file external');
```
------------

##005.fungsi-consolelog.html
```html
<html>
  <head>
    <meta charset="utf-8">
    <title>Belajar JS</title>
  </head>
  <body>
    <h1>belajar fungsi consol.log</h1>
    <script>
      console.log("Tulisan ini dari fungsi console.log javascrpit");
      console.log(999);

    </script>

  </body>
</html>

```

Silahkan ketik code javascript di atas, lalu save dengan format .html lalu jalankan dengan browser, setelah itu klik kanan - inspect atau dengan menekan shorcut CTRL+SHIFT+I, pilih tab console, maka akan muncul tulisan yang di hasilkan dari fungsi console.log di atas.
Jadi fungsi console.log() ini adalah untuk menampilkan sesuatu di tab console pada inspect element browser.

------------

Selanjutnya, penjeasan code ada pada file yang terupload di atas agar lebih mudah.
