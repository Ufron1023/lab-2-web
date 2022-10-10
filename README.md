# lab2web
## langkah langkah pratikum
### 1. membuat dokumen html
buat lah dokumen html seperti berikut
![image](/screenshot/ss1.png)
selanjutnya buka pada browser untuk melihat hasilnya
![image](/screenshot/ss2.png)
### 2. mendeklarasikan css internal
kmudian tambahkan deklarasi css internal sperti berikutn pada bagian head dokumen
![image](/screenshot/ss3.png)
selanjunya simpan perubahan yang ada,dan lakukan refresh pada browser untuk melihat hasilnya
![image](/screenshot/ss4.png)
### 3. menamahkan inline css 
kmudian tambahkan deklarasi inline css pada tag `<p>`
`<p style="text-align: center; color: #ccd8e4;">`
simpan kembali dan refresh kembali browser untuk melihat perubahanya
![image](/screenshot/ss5.png)
### 4. membuat css eksternal
Buatlah file baru dengan nama style_eksternal.css kemudian buatlah deklarasi CSS seperti berikut.
![image](/screenshot/ss6.png)
Kemudian tambahkan tag `<link>` untuk merujuk file css yang sudah dibuat pada bagian `<head>` <p>
`<head>` <p>
`<!-- menyisipkan css eksternal -->`
`<link rel="stylesheet" href="style_eksternal.css" type="text/css">` <p>
`</head>` <p>
Selanjutnya refresh kembali browser untuk melihat perubahannya.
![image](/screenshot/ss7.png)
Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector. Pada file style_eksternal.css, tambahkan kode berikut.
