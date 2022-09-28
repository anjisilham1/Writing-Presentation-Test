# <center>**Rangkuman Minggu Ke 1**

## **Unix Command Line**<hr>
- ### **Command Line Interface(CLI)**
  <div align="justify">CLI adalah singkatan dari Command Line Interface. Singkatnya, dengan CLI sebagai program, pengguna bisa memberikan perintah dalam bentuk teks, kemudian memberikan instruksi dan melakukan tugas tertentu.
  
- ### ***shell***
  <div align="justify">Program ayng digunakan untuk berkomunikasi  atau memerintah sistem 

- ### **Terminal Emulator**
  <div align="justify">Aplikasi untuk mengakses CLI

- ##### **CONTOH CLI**
  - <dIV align="justify">sh
  - bash
  - zsh
  - cmd.exe

## GIT & GITHUB<hr>

- ## **Git**
  - <div align="justify">adalah Tool untuk programer atau versi perangkat lunak yang digunakan untuk kontrol versi atau proyek perangkat lunak manajemen kode yang dibuat oleh Linus Torvalds. Awalnya, GIT digunakan untuk pengembangan kernel linux


  - <div align= "justify">
     git juga sebagi  vesrsion control system.
  - <div align="justify"> Apa itu Version Control System Tugasnya adalh mencatat setiap perubahan pada file (termasuk code yang kita buat) pada suatu  proyek baik dikerjakan secar individual maupun tim.
  - <div align="justify">Git biasanya digunakan para programer sebagai tempat penyimpanan file pemrograman mereka, karena lebih efektif.

  <div align="justify">macam-macam Git

  - <div align="justify">GIT status
  - Git Add
  - Git Commit
  - Git push
  - Git brand
  - Git checout


 ### Aladan kenapa Git dan Github tools yang wajib digunakan
  Dengan menggunakan GIT dan Github, kamu akan bisa bekerja dalam sebuat tim. **Tujuan besarnya** adalah kamu bisa berkolaborasi mengerjakan proyek yang sama tanpa harus repot copy paste folder aplikasi yang terupdate.
  Kamu juga tidak perlu menunggu rekan dalam satu tim kamu menyelesaikan suatu program dahulu untuk berkolaborasi. Kamu bisa membuat file didalam projek yang sama atau membuat code di file yang sama dan menyatukannya saat sudah selesai.

&nbsp;

### Langkah bekerja dengan Git untuk mempublish ke GitHub
- Masuk ke dalam git bash dengan cara klik kanan pada file yang akan di      publish lalu klick "Git Bash Here"


- membuat Repository dengan masuk ke dalam Aplikasi GitHub


- Lakukan beberapa Command di dalam git
  - git init <nama_proyek>, untuk membuat repositori baru

    ```
    git init namarepo
    ```
    <div align="justify">Karena kita sudah membuat repositoy sebelumnya maka kita bisa gunakan ini langsung tanpa harus memberi nama repo baru

    ```
    git init.
    ```
  - git status, digunakan untuk melihat apakah terjadi perubahan atau tidak pada git
    ```
    git status
    ```
  - git add <nama_file>, di gunakan untuk manambah file baru/ menambah perubahan pada file
    ```
    git add namafile   
    ```
    ```
    git add . 
    ```
  - git commit -m "Pesan", di gunakan untuk menyimpan perubahan pada git
      ```
      git commit -m "Pesan"
      ```
  - git remote, digunakan untuk menghubungkan project local yang tlah kita buat ke repository
    ```
    git remote add origin "Link repository pada GitHub"
    ```
  - git push, diguanakan untuk mengirim perubahan file ke remote repository
    ```
    git push -u origin master
    ```



- ## **HTML** <hr>
  <div align="justify">Apa itu Html dan bagaimana cara kerjanya?

  - <div align="justify">HTML singkatan dari Hipertext Markup Language adalah suatu bahasa yang menggunakan tanda-tanda tertentu (tag) untuk menyatakan kode-kode yang harus ditafsirkan oleh browser agar halaman tersebut dapat ditampilkan secara benar
  - HTML digunakan untuk menampilkan konten pada browser

   <div align="justify">Sebagai programer kita akan selalu menggunakan berbagai macam tool.
  Ada 2 tools utama yang harus dipersiapkan untuk membuat HTML yaitu:

  - <div align="justify">Browser
  - Code igniter
  <div align="justify">Aplikasi yang digunakan Visual studio code. Visual studio code adalah code editor yang dikembangkan oleh tim engineer Microsoft.

  <div align="justify">Biasanya programer memilih yang banyak digunakan sesama developer. jika suatu tools atau bahasa pemrograman banyak digunakan oleh komunitas,itu artinya calid atau wajib digunakan.


<div align="justify">Html struktur

- contoh

<div align="justify">
<img src="gambar/download.png"/>

- <div align="justify">Html terususn  sebagai kesatuan dari sebuah tingkatan 

- saat sebuah element berada didalam element lain, maka disebut child element
- Element yang berada diatas element lain disebut parent element.


<div align="justify">contoh

```html
<body>
   <P>
    This paragraf is a child of the body
   </P>
</body>
```

```html
<body>
  <div>
  <h1>
    Sibling to p, but also grandchild of body
  </h1>
  <p>
    Sibling to h1, but also grandchild of body
  </p>
  </div>
</body>
```

### HTML Atribut
  Property dari subah element HTML. Contohnya id, class, name.

- ### Single Tag atau Singular Tag 

  ```html
  <br> <!-- Membuat baris baru -->
  <hr> <!-- Membuat Garis Horizontal -->
  <img src=""/> <!-- Untuk Menmapilkan gambar-->
  ```

- ### Paired Tag atau Double Tag

  ```html
  <h1></h1> 
  <p></p>
  ```

- ### Html Command
  <div align="justify">Digunakan untuk memberikan komentar atau keterangan pada suatu line code

  ```html
  <!-- Komentar -->
  ```
- ### Salah satu cara menjalankan HTML dengan Live server
  <div align="justify">yakni dengan membuka run code HTML melalui live server maka akan membuka hasil run dari code html yang telah kita buat secara langsung.

- ### Pembuatan Tabel pada HTML
  ```html
  <body>
    <table border="1" cellspacing="0">
        <thead>
            <tr>
                <th>Head 1</th>
                <th>Head 2</th>
                <th>Head 3</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Data1</td>
                <td>Data2</td>
                <td>Data3</td>
            </tr>
        </tbody>
    </table>
  <body>
  ```

  
<br>

- ### Semantic HTML
  <div align="justify">Semantic adalah menggunakan element html yang sesuai dengan kebutuhan konten. Contoh seperti Header, Nav , Footer, Articel, Section, dll.
  <br>
  Penulisan nya seperti berikut :

  ```html
  <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <header>
            <h1>Website Kiki</h1>
        </header>

        <nav>
            <a href="#">Home</a>
            <a href="#">About</a>
            <a href="">Contact</a>
        </nav>

        <article>
            <h1>Selamat Datang di Website KIKI</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit.Aliquid necessitatibus hic odit in fugit.</p>
        </article>

        <footer>
            <p class="title">&copy; Kiki Andrianto Website 2022</p>
        </footer>
    </body>
    </html>
  ```

## **CSS**
- ### Penjelasan CSS
  <div align="justify">CSS (Cascading Style Sheets)adalah bahasa yang digunakan untuk mendesain halaman website.
  Dengan CSS, kita bisa mengubah warna, menggunakan font custom, editing text format, mengatur tata letak, dan lainnya.

- ### Struktur CSS
  ```css
  .elementshtml{
    property : value
  }
  ```
- ### CSS Comment
  <div align="justify">Dengan menggunakan CSS Comment, kita dapat memberikan penjelasan maksud dari line code yang kita kerjakan.

  ```css
  /* Komentar */
  ```

  ## 3 Cara Menggunakan CSS
  - **Inline Styles**
    <div align="justify">Inline styles adalah kita menambahkan CSS pada attribute element HTML

    ```html
    <P style="color : blue; font-size : 40px">Hello world</p>
    ```
 **Internal CSS**
    <div align="justify">Menambahkan kode Style pada html di bagian head.

- **Eksternal CSS**
  <div align="justify">Jika kita membutuhkan banyak code pada CSS, direkomendasikan untuk memisahkan code CSS di file tersendiri (extension .css) dan terpisah dari file HTML.
    <br>

 - Pada file index.html
      ```html
      <!DOCTYPE html>
      <html lang="en">
      <head>
          <meta charset="UTF-8">
          <meta http-equiv="X-UA-Compatible" content="IE=edge">
          <meta name="viewport" content="width=device-width, initial-scale=1.0">
          <title>Document</title>
          <link rel="stylesheet" href="style.css">
      </head>
      <body>
          <h1>Hello World</h1>
      </body>
      </html>
      ```

  - Pada file style.css
      ```css
      h1 {
        color : blue;
        font-size : 40px;
      }
      ```
<br>

 - ### CSS Tag Name
    <div align="justify">Kita bisa menggunakan Tag Elemen HTML secara langsung pada CSS.Jika menggunakan Tag Element, maka ini bersifat global.

    ```css
    h1 {
      color : blue;
    }
    ```
    <div align="justify">contoh seperti di atas akan merubah seluruh element h1 pada html menjadi warna biru

  - ### CSS-Class Name
    <div align="justify">Kita bisa menggunakan attribute class pada elemen HTML lalu memanggil nama class tersebut pada CSS.

    ```css
    .menuUtama {
      color : blue;
    }
    ```

  - ### CSS - Multiple Class
    <div align="justify">menggunakan lebih dari 1 class yang berbeda untuk 1 element HTML.

    ```css
    .menuUtama {
      color : blue;
      font-size : 24px;
    }
    .menuUtamaKedua {
      color : blue;
      font-size : 40px;
    }
    ```

- ### CSS - ID Name
    <div align="justify">Berbeda dengan Class Name. ID Name bersifat unik artinya hanya ada 1 nama ID pada 1 element HTML.
    Gunakan (#namaID) saat memanggil element ID HTML pada CSS
    
    ```css
    #Navigation {
      color : red;
    }
    ```
  - ### Chaining Selectors
    <div align="justify">Jika kita memiliki 3 tag elemen HTML pada CSS namun kita ingin ada 1 elemen HTML yang memiliki styling berbeda.

    ```css
    h1 .judulMusik{
      color : green;
    }
    ```

    ## **Flexbox**
- <div align="justify">FlexBox adalah cara untuk mengatur layout.
- Flexbox memiliki kemampuan untuk menyesuaikan layout secara otomatis.
- Konsep Sederhana
  <div align="justify">Flexbox memiliki 1 parent/container dan bisa beberapa child/item.
- Flex Direction
  properti flex-direction digunakan untuk mengatur letak item child.  ada 4 value flex-direction yang harus kamu ketahui:
  - row (default): secara default letak item child membentuk sebuah baris dari kiri ke kanan.
  - row-reverse: letak item child membentuk sebuah baris dari kanan ke kiri
  - column: letak item child membentuk sebuah baris dari atas ke bawah
  - column-reverse: letak item child membentuk sebuah baris dari bawah ke atas

  ```css
  .container {
    flex-direction : column;
  }
  ```
- Flex Wrap
  <div align="justify">flex secara default akan membuat tata letak item children dalam 1 line saja. flex akan menyesuaikan space yang ada.
  Property Flex Wrap :

  - no-wrap (default): secara default , flex tidak menggunakan flex-wrap
  - wrap: flex item akan memiliki beberapa line dari atas ke bawah  jika space dalam 1 line sudah full width.
  - wrap-reverse: kebalikan dari wrap yaitu lex item akan memiliki beberapa line dari bawah ke atas  jika space dalam 1 line sudah full width

- Flex Flow
  <div align="justify">properti flex-flow digunakan sebagai shortcut untuk set up flex-direction dan flex-wrap bersamaan.
  ada 4 value pada flex-flow:

  - row nowrap
  - column wrap
  - column reverse
  - row-reverse wrap-reverse

- Oreder
  <div align="justify">properti order pada flex adalah berfungsi untuk ordering item mana yang ingin kita atur posisinya berdasarkan urutan order.

  <br>

- ### Alignment
  - Justify-content
  <div align="justify">properti justify-content digunakan untuk mengatur tata letak dan space antar item child secara horizontal atau main axis.
  <div align="justify">justify-content memiliki 6 value yaitu:

    1. flex-start
    2. flex-end
    3. center
    4. space-between
    6. space-around
    7. space-evenly
    
    <br>
  
  - align-items
    <div align="justify">properti align-items digunakan untuk mengatur align dari item child secara vertikal atau cross axis.
    justify-content memiliki 5 value:

    - flex-start
    - flex-end
    - center
    - baseline
    - stretch

  - align-self
    <div align="justify">properti align-self digunakan untuk mengatur align item pada masing-masing item.
    align-self memiliki 5 value yang sama dengan align-items:

    - flex-start
    - flex-end
    - center
    - baseline
    - stretch

  - align-content
    <div align="justify">align-content digunakan untuk mengatur tata letak dan space antar item child secara vertikal atau cross axis.
    <div align="justify">align-content memiliki value yang sama dengan justify-content. bedanya ada 1 tambahan value yaitu stretch.


## **JavaScript**
- Javascript adalah bahasa pemograman yang sangat powerful yang digunakan untuk logic pada sebuah website
- Javascript juga dapat membuat website menjadi interaktif dan dinamis
- Javascript dijalankan melalui browser pada device setiap user. 

<br>

- **Syntax dan Statement**
  <div align="justify">Menggunakan syntax tertentu untuk membuat statement program, instruksi untuk djalankan/dieksekusi oleh web browser, compiler, ataupun intrepreter.
  <div align="justify">Contoh Alert :

  - Alert()
  - Prompt()
  - Confirm()

  ```javascript
  Prompt("teks")
  ```

  - Console Log
    <div align="justify">Console log adalah tempat kita untuk cek logic pemograman web yang kita kembangkan.Console log juga tempat kita untuk melakukan debugging (mengetahui error pada code).

  - Comments

    ```javascript
    // Single Comments
    /* Multiline Comments */
    ```

- **Tipe Data (Data Types)**
  <div align="justify">Klasifikasi yang kita berikan untuk berbagai macam data yang digunakan dalam programming.

  - number
    <div align="justify">Mengandung semua angka termasuk angka desimal.

    ```javascript
    let angka = 10;
    ```
  - string
    <div align="justify">Grup karakter yang ada pada keyboard laptop/PC kita yaitu letters (huruf), number (angka), spaces (spasi), symbol, dan lainnya.

    ```javascript
    let nama = "Kiki";
    ```
  - boolean
    <div align="justify">Tipe data yang hanya mempunyai 2 buah nilai.(TRUE dan FALSE)

    ```javascript
    let benar = true;
    let salah = false;
    ```

  - null
    <div align="justify">Tipe data yang diartikan bahwa sebuah variable/data tidak memiliki nilai.
  - undefined
    <div align="justify">Tipe data undefined adalah tipe data yang merepresentasikan varibel/data yang tidak memiliki nilai.

    ```javascript
    let a = "test"
    console.log(c); //undefined
    ```
  - object
    <div align="justify">koleksi data yang saling berhubungan (related). Tipe data pbject dapat menyimpan data dengan tipe data apapun (number, string, boolean, dan lainnya).


    - **Variabel**
  - variable adalah container/tempat untuk menyimpan sebuah nilai
  - Ada 3 cara mendefinisikan sebuah variabel.

    - var
    - let
    - const

  ```javascript
  var nama = "txt";
  let nama1 = "txt";
  const nama2 = "txt";
  ```

- Assignment Operator (=)
  <div align="justify">Assignment operator digunakan untuk menyimpan sebuah nilai pada variabel.

- Increment dan Decrement
  <div align="justify">Gunakan increment atau decrement untuk menambah atau mengurangi sebesar 1 nilai.
- Arithmetic operator 
  <div align="justify">adalah operator yang melibatkan operasi matematika.

  - Tambah (+)
  - Kuramg (-)
  - Perkalian (*)
  - Pembagian (/)
  - Modulus (%)

  ```javascript
  console.log(3+4); // 7
  console.log(8-4); // 4
  console.log(3*4); // 12
  console.log(8/4); // 2
  console.log(8%2); // 0
  ```

  - Comparison Operator
  <div align="justify">Operator yang membandingkan satu nilai dengan nilai lainnya.
  <div align="justify">Simbol comparison operator :

  - Lebih kecil dari : <
  - Lebih besar dari: >
  - Lebih kecil atau sama dengan: <=
  - Lebih besar atau sama dengan: >=
  - Sama dengan: ===
  - Tidak sama dengan: !==

- Logical Operator
  <div align="justify">Logical operator biasa digunakan untuk sebuah CONDITIONAL pada pemograman.Menghasilkan nilai BOOLEAN yaitu TRUE or FALSE.

  - AND operator : &&
  - OR operator: ||
  - NOT operator: !


<br>

## **Algoritma dan Pseudocode**
- ### Algoritma
  - Algoritma adalah deskripsi berupa step-step yang dibutuhkan untuk menyelesaikan suatu masalah
  - Kualitas wajib dari Algoritma

    - Input dan output harus didefinisikan terlebih dahulu dengan tepat
    - Setiap step harus benar-benar clear dan tidak ambigu
    - Algoritma seharusnya tidak mengandung suatu code pada bahasa pemograman   tertentu. Algoritma harus dibuat agar dapat digunakan dalam bahasa pemograman apapun.

  - Kenapa harus belajar Algoritma?
    - Programming itu adalah algoritma dan struktur data
    - Data struktur digunakan untuk mengelola/manajemen sebuah data
    - Dan Algoritma yang akan menyelesaikan suatu permasalahan menggunakan data tersebut.

  - Contoh Algoritma Sederhana
    ```
    input 1 = 5
    input 2 = 10
    output = input 1 +input 2
    print ("Result", output) 
    ```
- ### Pseudocode
  - Pseudocode adalah menuliskan algoritma dengan umumnya bahasa inggris sebelum kita implementasikan ke bahasa pemograman tertentu.
  - Panduan menulis pseudocode

    - Menggunakan HURUF BESAR pada kata kunci (key commands). 
      CONTOH: IF number is > 10 THEN …
    - 1 statement =  1 baris 
    - Gunakan indentasi
    - Please please be specific
    - Tapi tetap simpel

  - Contoh Pseudocode

    ```
    Deklarasi 
    Jam, Detik 
    INPUT jam 
        Convert Jam ke Detik (*3600)
    DISPLAY result
    ```
  
  - Conditional
    <div align="justify">Conditional digunakan saat dibutuhkan percabangan kasus. Komputer akan melakukan suatu tindakan jika suatu kondisi terpenuhi.

    ```
    If "Lapar"
    Do "Makan"

    Display "Saya jadi kenyang"
    ```
  - Looping
    <div align="justify">Komputer dapat melakukan sebuah proses yang sama berulang-ulang.Jika membutuhkan perulangan dalam kasus tertentu, kita bisa menggunakan Looping.

    ```
    i = 1
    for (i, 1<=5 , i++){
      print i
    }
    ```

    - Ada 2 jenis/pandangan yang harus kita ketahui dari Algoritma
  
    - Gunakan algoritma kita sendiri dalam menyelesaikan masalah (Melatih logika kita untuk berpikir)
    - Gunakan algoritma yang sudah umum disediakan jika dibutuhkan


