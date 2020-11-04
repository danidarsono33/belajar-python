belajarpython
# LATIHAN PYTHON PERTEMUAN KE 5-6

BAHASA PEMROGRAMAN  
TENIK INFORMATIKA 
UNIVERSITAS PELITA BANGSA

NAMA : DANI DARSONO

NIM  : 312010189

KELAS: TI.20.B.1

DOSEN : Agung Nugroho ,S.kom,M.kom

Tugas : membuat program python latihan 1_input data ,lab 1 penggunaan end & string format dan Lab 2_konversi nilai variabel 

 > Membuat File Baru/Proyek Python Menggunakan PyCharm
 
 PyCharm adalah lingkungan pengembangan terintegrasi (IDE) yang digunakan dalam pemrograman komputer, khusus untuk bahasa Python. Aplikasi ini dikembangkan oleh sebuah perusahaan yang berasal dari Ceko bernama JetBrains .
 
Untuk membuat suatu file baru/ proyek python menggunakan PyCharm, pertama kita klik icon Pycharm

![1](https://user-images.githubusercontent.com/73014427/97963420-b4a17e00-1de9-11eb-9502-c5a399afda9e.png)

lalu klick " creat new project " pada jendela pycharm yang muncul.

![2](https://user-images.githubusercontent.com/73014427/97963860-6345be80-1dea-11eb-866c-450fe0a930a2.png)

Atau bisa juga dilakukan melalui menu File-> New Project.

Setelah itu, kita akan diminta untuk mengisi nama proyeknya. Isi saja nama proyeknya “BelajarPython”. Lalu tekan Create.

![3](https://user-images.githubusercontent.com/73014427/97964619-a2c0da80-1deb-11eb-97c4-c2a98debb11e.png)

Selanjutnya, silahkan tambahkan file python dengan klik kanan pada direktori proyek, kemudian pilih New -> Python File.

![4](https://user-images.githubusercontent.com/73014427/97965294-b751a280-1dec-11eb-822d-8ff6c03ff017.png)


. 01.latihan 1_ input biodata

tugas latihan 

![5](https://user-images.githubusercontent.com/73014427/97967365-b3734f80-1def-11eb-87d4-19c4b9585242.png)


kita ketik perintah pyhon :

![6](https://user-images.githubusercontent.com/73014427/97968901-ddc60c80-1df1-11eb-8f14-c1822b18f843.png)



untuk menjalankan kode python yg sudah kita buat tadi ,klik kanan pada file yg kita buat lalu pilih run atau bisa
juga tekan ctrl + shift +f10

![7](https://user-images.githubusercontent.com/73014427/97981152-6ea5e380-1e04-11eb-9ac7-b808de778ffc.png)

untuk program mengisi nilai variabel tipe data teks (string) maka harus di apit dengan tanda petik ("....")

  .02.lab _ 1 penggunaan end ,separator & string format

tugas lab 1 :

![9](https://user-images.githubusercontent.com/73014427/97983906-90a16500-1e08-11eb-920e-3b94b6c6a575.png)

kita buat  New file > simpan sesuai nama file (seperti tutorial di atas), lalu kita ketik 
kode perintah python :

![10](https://user-images.githubusercontent.com/73014427/97985226-9730dc00-1e0a-11eb-9d26-1deb5c36783d.png)

![11](https://user-images.githubusercontent.com/73014427/97985455-dd863b00-1e0a-11eb-8d64-838dbfebf5c1.png)

tampilan setelah di run 

![12](https://user-images.githubusercontent.com/73014427/97985911-816fe680-1e0b-11eb-854f-2dd858170024.png)

- untuk mengambil input menggunakan
fungsi input()

input ()-> untuk mengambil nilai sesuai variabelnya .

- untuk Output program di atas , python menggunakan 
fungsi print().

secara default, kita dapat menambahkan spasi di antara variabel . akan tetapi kita juga bisa menggubahnya 
dengan menambahnya dengan code end,separator.

print(*object ,sep ='  ' end='/n)

*object -> variabel ,sep -> separatornya ,
end -> akhir dari perintah 

- untuk Output Formating menggunakan 
fungsi str.format ()

-kurung kurawal { } digunakan sebagai placeholder.-kita menentukan urutan yang dicetak dengan menggunakan 
angka (tupel index )

 .02.lab 2_Konverse Nilai Variabel 
 
Tugas lab 2 :

![13](https://user-images.githubusercontent.com/73014427/97988450-96e70f80-1e0f-11eb-8a74-f3121b838687.png)

kita buat New File -> simpan sesuai nama file ( seperti tutorial di atas ), lalu kita ketik 
kode perintah python 

![15](https://user-images.githubusercontent.com/73014427/97990034-efb7a780-1e11-11eb-9403-4b470563c5fd.png)

kode python yang kita masukan terdapat eror.
TypeEror:%d format :a number is required ,not str 

pada eror tersebut terbaca bahwa variabel a adalah string , yang seharusnya di baca oleh sytem adalah number 
/interger ,bagaimana cara memperbaiki eror tersebut?

kita lihat pada baris ke 7 ( di notifikasikan terbaca eror terletak pada baris ke 7), yaitu pada pemformatan. 
format() adalah interger,sedangkan jika berupa string maka akan ada tanda petik dua ("..") pada performatan.  
format ()

kita akan terfokus pada variabel a dan b

pada line ke 3 tertulis sytax :
a=input ("masukan nilai a")

sedangkan pada line ke 4 tertulis sytax :
b=input ("masukan nilai b")

untuk membuat inputan berupa interger /angka harus ditambahkan sytax int() pada format input() , yang seharusnya 
di tulis adalah :
kita akan ulangi semua sytax pada file ini seperti gambar di bawah ini 

![14](https://user-images.githubusercontent.com/73014427/97989986-df9fc800-1e11-11eb-85e7-310306050fe3.png)

kita akan coba lagi untuk run file tersebut ,maka akan muncul seperti gambar di bawah ini :

![16](https://user-images.githubusercontent.com/73014427/97994899-6a83c100-1e18-11eb-8d6e-c73b3962aba6.png)


semua file sudah berhasil di tampilkan pada program .

cukup sekian penjelasan dari saya ,

TERIMA KASIH 







