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

### Contoh di file :
- `object.html`