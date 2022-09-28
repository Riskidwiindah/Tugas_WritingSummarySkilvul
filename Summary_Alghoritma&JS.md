## Alghoritma 


Taukah kalian tanpa kita sadari bahwa selama ini setiap tindakan kita itu mencerminkan proses alghoritma. Pasti kalian langsung bingungkan apa itu alghoritma? Jadi pengertian alghoritma yaitu tahapan-tahapan yang tersusun secara sistematis sehingga membentuk suatu proses. Syarat dari suatu alghoritma ialah: kejelasan setiap step by stepnya, terdapat input dan menghasilkan output, serta mengandung suatu code dari bahasa pemograman yang ditentukan.

Kemudian kenapa kita harus mempelajarinya? Sebab di saat kita membuat program alghoriitma ini adalah modal penting guna memahami cara kerja atau akur dari codingan yang dibuat. Alghoritma sendiri memiliki 3 jenis diantaranya:

1. Algoritma Deskriptif. Cukup mudah pengaplikasian alghoritma jenis ini, dengan bahasa sehari-hari dan setiap tahapan ditulis secara berututan sudah dapat dikategorikan alghoritma jenis ini.
2. Alghoritma Flowchart. alghoritma ini sudah mulai menggunakan bahasa codingan yang digunakan serta dibantu dengan bentuk-bentuk persegi, jajargenjang, dll disetiap tahapannya. 
3. Algoritma Pseudocode. Algoritma jenis ini lebih mendekati bahasa code yang akan dibuat. Biasanya akan ditulis dengan format bahasa inggris. 

## Pengenalan Java Script


Java Script(JS) bukanlah Java karna mereka berbeda. JS berguna sekali membuat sebuah website dapat melakukan intaraksi dengan penggunanya dan merubah website yang awalnya statis menjadi dinamis. Menjalankan JS cukup dengan mempersiapkan browser seperti google, mozilla dll. Contoh syntax JavaScript:
1. Alert() yaitu mempilkan alert seperti pop up kotak dialog
2. Prompt() digunakan apabila membutuhkan inputan data dari pengguna. Nantinya akan mucul seperti kotak dialod yang terdapat kolom inputan.
3. Confirm() dibutuhkan untuk mengkonfirmasi sesuatu pada user. akan muncul kotak dialog dan pengguna diberiberi button suatu pilihan.
4. Console.log yaitu hal dasar yang wajib diketahui berfungsi untuk menguji logika program yang dibuat atau print data yang akan ditampilkan di bagaian console pada browser
5. comment. Kegunaan comment masih sama yaitu untuk menjelaskan code program kepada sesama programmer. Terdapat 2 macam comment: single comment (//) dan multiline comment (/**/)

## Tipe Data & variabel JS


Javascript memiliki 6 tipe data:
1. Number
2. String
3. Boolean
4. Null
5. Undefined
6. Objek

Pada javascript punterdapat penggunaan variabel. Variabel itu digunakan sebagai tempat penampunya nilai. Ada 3 macam variabel:
1. Var
2. Let
3. Const

Perbedaan diantaranya ialah jika menggunakan var setiap ada nama variabel yang sama ia akan selalu berubah sesuai varibel yang terbaru. Jika menggunakan let apabila terdapat inisialisasi nama variabel yang sama maka langsung error. Jika menggunakan const nilai atau value variabelnya tidak bisa diubah. 

## Operator JS


1. Assigment operator. Operator yang digunakan untuk memasukan nila kedalam variabel (=)
2. Aritmatik operator. operator yang melibatkan operasi matematika. Contohnya: +, -, *, /, %
3. Comparison operator. digunakan untuk mengcompare, membandingkan dua nilai yang menghasilkan teru or false. Contohnya: <, >, <=, >=, ==, ===, !==, !=
4. Logical operator. umumnya digunakan untuk melogika suatu kondisi kemudian menghasilkan nilai tru or false. Contoh simbolnya: && (dan), || (atau), ! (tidak)

## Conditional JS


Artinya kita sudah memasuki pembahasan pembuatan sebuah kondisi di javascript. jika ada kondisi maka tak luput dengan penggunaa if, else if, dan else. Untuk lebih jelasnya: if (jika), else if (jikalau), dan else (kondisi akhir dari kondisi sebelumnya). sysntax penulisannya yaitu:

if (kondisi){
    aksi
} else{
    aksi
}

atau

if (kondisi){
    aksi
} else if(kondisi){
    aksi
}else{
    aksi
}

Tidak hanya menggunakan if kita juga dapat menggunakan syntax switch. Contohnya:

switch (kondisi){
   case x:
    aksi
    break
    case y:
    aksi
    break
    default:
    aksi
}

Penggunaa switch disetiap casenya diwajibkan ada break sebagai penanda jika kondisi true maka pemeriksaan akan berhenti.

## Looping JS


Pengulangan (looping) digunakan jika sebuah kasus yang memerlukan pengulangan. Intinya apabila terdapat kasus yang memerlukan menampilkan banyak nilai, kita tidak mungkin menuliskannya satu persatu. Maka diperlukannya looping. looping sendiri terdapat berbagai macam yaitu for, while, do while. 
1. For loop. Kondisi perulangan yang sebelumnya kita sudah mengetahui berapa jumlah pengulangan yang dibutuhkan. Jadi systx penulisannya:
 for (kondisi awal; kondisi akhir; incerement){
    aksi
 }

 hasilnya:

 for (let i=0; i<8; i++){
    console.log(i)
 }

 2. While. penggunaan perulangan ini ketika terjadi kasus yang kita tidak tahu akan berapa kali pengulangan ini dilakukan. Contoh:
 while (kondisi) {
    aksi
 }

hasilnya:

let i=0
while (i<100){
    console.log(i)
    i++
}

pembahasannya selama i kurang 100 maka akan melakukan print terhadap nilai i, lalu i melakukan incerement dan terus akan berulang.

3. do while. pengulangan ini setidaknya akan menghasilkan satu kali hasil. Contoh syntaxnya
do {
    aksi
} while (kondisi)