## Created_by_21343019_Arafil Azmi

Pada JS 9 ini kita diperkenalkan dengan Java Class yang dimana terdapat object, properties dan behavior. Object itu merupakan instansiasi dari sebuah class contoh object yaitu mobil,motor,kucing dll. Object ini terdapat sifat atau atribut dan tingkah lakunya yang dimana properties merupakan atribut dan behavior adalah tingkah laku. Tingkah laku berarti adalah apa saja yang bisa dilakukan oleh object tersebut.

Contohnya : Objectnya adalah laptop, propertiesnya adalah pemilik, warna, merk, dan ukuran layar dan behaviornya laptop menyala, laptop mati, laptop sleep dll.

Berikut penjelasan dari beberapa program latihan :

1. Program Latihan 1 merupakan program pass by value artinya data yang dipanggil dalam method pemanggil adalah nilai dari variabelnya, jika nilai variabel dalam suatu 
   method dipanggil dalam method pemanggil maka nilai variabel dalam method pemanggil tidak akan berubah. Bisa dilihat dalam program terdapat method tes dengan 
   variabel j dan bertipe int dan sudah diberi nilai 33 dan pada method main terdapat variabel i bertipe int dengan nilai variabelnya 10. Dalam method main kita 
   mencetak nilai variabel i = 10 kemudian kita memanggil method test dan didalam method test itu nilai variabelnya 33 dan kita mencetak nya kembali maka tetap nilai 
   variabel i = 10. Pass by value ini berlaku di tipe data primitive. Jika kita menambahkan perintah cetak pada method test maka nilai variabel akan keluar sesuai 
   dalam method test yaitu 33 namun tidak akan merubah nilai variabel dalam method main. 
   
2. Program Latihan 2 merupakan program pass by reference yaitu merupakan kebalikan dari pass by value yang artinya data yang dipanggil dalam method pemanggil adalah 
   reference atau alamat dari variabelnya. jika nilai variabel dalam suatu method dirubah dan method itu dipanggil dalam method pemanggil maka nilai varibalenya dalam 
   method pemanggil akan berubah. Bisa dilihat dalam program tersebut terdapat method variabel ages dalam bentuk array bertipe int dan terdapat perintah perulangan
   menggunakan for dimana ungkapannya ( int i = 0; i < ages.length ( i kurang dari panjangnya nilai array pada ages ); i++) dan pernyataanya perintah mencetak semua 
   nilai pada array ages. Maka akan tampil 10 11 12, kemudian memanggil method test yang dimana terdapat variabel arr dalam bentuk array bertipe int dan terdapat
   perintah perulangan yang diambil dari panjang dari array arr dimana arr ini diganti menjadi ages pada method main dan pernyataannya arr [i] = i + 50 artinya nilai i 
   akan ditambah 50 dan akan diulang sesuai dengan panjang dari array arr yang nilainya itu diambil dari array ages. Maka ketika kita mengulangi perintah perulangannya 
   nilai variabel dari ages akan berubah dan akan menampilkan 50 51 52 karena data yang dibawa adalah alamatnya bukan nilai variabelnya. pass by reference menggunakan
   tipe data seperti object dan tipe data array.
   
3. Program Latihan 3 merupakan program equals (sama dengan) pada string atau membandingkan. Pada program terdapat variabel str1 dan str2 bertipe string dan str1 sudah 
   di inisialiasi dan str2 itu sama dengan str1 kemudian terdapat perintah mencetak dan dibandingkan object str1 dengan str2 menggunakan operator ( == ) ternyata 
   objectnya sama dan itu bernilai benar. Setelah itu kita membuat object baru untuk str2 dengan nilai sama dengan str1 dan setelah kita cetak dan dibandingkan
   menggunakan operator ( == ) maka objectnya sudah berbeda maka false dan kita menggunakan equals yang dimana equals ini membandingkan valuenya apakah sama atau 
   tidak.Jika tadi kita sudah membuat object baru untuk str2 dan nilainya itu dari str1 maka untuk perbandingan equals untuk value itu benar atau true.
   
4. Program Latihan 4 terbagi menjadi 2 class yaitu class Elevator dan ElevatorTest pada package atau folder yang sama. Pada class Elevator terdapat variabel doorOpen
   bertipe boolean, current floor bertipe int, TOP_FLOOR bertipe int dan BOTTOM_FLOOR bertipe int yang masing - masing sudah terinisialisasi dan memiliki access 
   modifier public yang artinya dapat diaksess dari mana saja dan pada class Elevator sudah dibuat method - method yang berisikan perintahnya masing - masing.
   Kemudian untuk class ElevatorTest kita membuat object baru dengan nama myElevator dari class Elevator. Pada class ElevatorTest ketika kita sudah membuat object 
   baru dari class Elevator yang artinya kita bisa mengakses yang terdapat pada class Elevator dengan menggunakan object lalu ( . ) lalu apa yang mau kita aksess.
   Pada program class ElevatorTest itu kita mengaksess method - method yang sudah dibuat pada class Elevator maka isi dari method - method class Elevator akan muncul
   pada class ElevatorTest.
   
