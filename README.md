# Pengenalan Object Oriented Programming
## Apa itu Object Oriented Programming?
- Object Oriented Programming adalah sudut pandang bahasa pemrograman yang berkonsep “objek”
- Ada banyak sudut pandang bahasa pemrograman, namun OOP adalah yang sangat populer saat ini.
- Ada beberapa istilah yang perlu dimengerti dalam OOP, yaitu: Object dan Class

## Apa itu Object?
Object adalah data yang berisi field / properties / attributes dan method / function / behavior


## Apa itu Class?
- Class adalah blueprint, prototype atau cetakan untuk membuat Object
- Class berisikan deklarasi semua properties dan functions yang dimiliki oleh Object
- Setiap Object selalu dibuat dari Class
- Dan sebuah Class bisa membuat Object tanpa batas

## OOP di JavaScript
- JavaScript sendiri sebenarnya sejak awal dibuat sebagai bahasa prosedural, bukan bahasa pemrograman berorientasi objek
- Oleh karena, implementasi OOP di JavaScript memang tidak sedetail bahasa pemrograman lain yang memang dari awal merupakan bahasa pemrograman OOP seperti Java atau C++


# Membuat Constructor Function
## Membuat Object
- Sebenarnya kita sudah belajar tipe data object, dengan cara membuat variable dengan tipe data object
- Namun pembuatan object menggunakan tipe data object, akan membuat object yang selalu unik, sedangkan dalam OOP, biasanya kita akan membuat class sebagai cetakan, sehingga bisa membuat object dengan karakteristik yang sama berkali, kali, tanpa harus mendeklarasikan object berkali-kali seperti menggunakan tipe data object

## Membuat Constructor Function
- Sebelum EcmaScript versi 6, pembuatan class, biasanya menggunakan function. Hal ini dikarenakan sebenarnya JavaScript bukanlah bahasa pemrograman yang fokus ke OOP
- Untuk membuat class di JavaScript lama, kita bisa membuat function
- Function ini kita sebut dengan Constructor Function

## Membuat Object dari Constructor Function
- Setelah kita membuat class, jika kita ingin membuat object dari class tersebut, kita bisa menggunakan kata kunci new, lalu diikuti dengan nama constructor function nya 


### Contoh di file :
- `object.html`


# Property di Constructor Function
## Property di Constructor Function
- Sebenarnya setelah kita membuat object, kita bisa dengan mudah menambahkan property ke dalam object tersebut hanya dengan menggunakan nama variable nya, diikuti tanda titik dan nama property
- Namun jika seperti itu, alhasil, constructor function yang sudah kita buat tidak terlalu berguna, karena property nya hanya ada di object yang kita tambahkan property
- Untuk menambahkan property di dalam semua object yang dibuat dari constructor function, kita bisa menggunakan kata kunci this lalu diikuti dengan nama property nya

### Contoh di file :
- `object.html`


# Method di Constructor Function
- Sama seperti pada tipe data object biasanya, kita juga bisa menambahkan method di dalam constructor function
- Jika kita tambahkan method di constructor function, secara otomatis object yang dibuat akan memiliki method tersebut

### Contoh di file :
- `object.html`
