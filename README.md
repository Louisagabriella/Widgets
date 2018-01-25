# My Garden
Android AppWidgets lesson

## The app
My Garden adalah permainan sederhana yang memungkinkan Anda menambahkan tanaman ke kebun Anda dan membuat mereka tetap hidup dengan menyiramnya tepat waktu.
Aplikasi ini menggambarkan kekuatan widget widget dan widget dengan mempermudah pengguna untuk memantau dan menyiram tanaman mereka dari layar awal.

## Initial Commit Screenshots

![screenshot_20180124-191432](https://user-images.githubusercontent.com/21364340/35390027-de40ce5c-018e-11e8-9e66-28abef7c0c7b.png)
![screenshot_20180125-202636](https://user-images.githubusercontent.com/21364340/35390732-468771d0-0191-11e8-9ee8-007a6d03da3f.png)
![screenshot_20180125-202643](https://user-images.githubusercontent.com/21364340/35390734-4ad57796-0191-11e8-9175-0ba929d61129.png)
![screenshot_20180125-202651](https://user-images.githubusercontent.com/21364340/35390736-4dfa26b0-0191-11e8-8604-022c6be7e0c7.png)
![screenshot_20180125-202658](https://user-images.githubusercontent.com/21364340/35390737-4e895e7a-0191-11e8-89b2-3af2698f25a8.png)
![screenshot_20180125-202701](https://user-images.githubusercontent.com/21364340/35390739-4f4e6b5c-0191-11e8-95fe-089e0348e4c5.png)
<br>
PENJELASAN: <br>
<ol>
  <li> Bentuk icon aplikasi saat diinstal di Hp android seperti screenshoot ke-1. </li> 
  <li> Saat pertama kali aplikasi dibuka maka akan seperti secreenshoot urutan ke-2 </li>
  <li> Saat kita menekan tombol + pada screenshoot ke-2 maka akan muncul halaman seperti screenshoot ke-3. Yang mana jika kita menekan "Vine" akan menambah tanaman "Vine" dan jika menekan "Cactus" maka akan menambah tanaman "Cactus" hingga seperti pada screenshoot ke-4.</li> 
  <li> Saat kita memilih(menekan) salah satu dari banyak tanaman pada screenshoot ke-4 tersebut, maka akan berganti ke halaman seperti screenshoot urutan ke-5 atau screenshoot ke-6. Ada tiga button atau perintah 1. seperti tanda panah kembali yang berfungsi untuk kembali ke halaman sebelumnya, 2. simbol mata air yang berfungsi untuk memberikan air atau menyirami tanaman, dan 3. simbol gunting yang digunakan untuk memotong pohon, jika kita memotong pohon sama saja kita menghapus pohon tersebut jadi nanti pohonnya tidak muncul lagi atau hilang. Ada dua peringatan yang berbentuk seperti kalender memberitahukan bahwa seberapa lama tanaman itu ditanam dan jam yang bertulisakan jam itu seberapa lama atau sejak kapan tanaman itu di siram </li>
</ol>

## AddNewWidget Commit Screenshots
![screenshot_20180125-211241](https://user-images.githubusercontent.com/21364340/35392813-e7edc5a0-0197-11e8-8ad8-f996576acb0a.png)
![screenshot_20180125-211245](https://user-images.githubusercontent.com/21364340/35392817-e83f03c0-0197-11e8-8b27-e217d98ee526.png)
![screenshot_20180125-211250](https://user-images.githubusercontent.com/21364340/35392818-e89ad006-0197-11e8-9b3c-b627e0a7e93d.png)
![screenshot_20180125-211258](https://user-images.githubusercontent.com/21364340/35392819-e8eef3c0-0197-11e8-9285-39735f96f024.png)
![screenshot_20180125-211306](https://user-images.githubusercontent.com/21364340/35392821-e95b71ee-0197-11e8-813b-709923c75684.png)
![screenshot_20180125-211317](https://user-images.githubusercontent.com/21364340/35392822-e9acc260-0197-11e8-87c3-a4b46f78c4f0.png)
![screenshot_20180125-210508](https://user-images.githubusercontent.com/21364340/35392804-e6d1e99e-0197-11e8-9f95-749be5395b75.png)
![screenshot_20180125-210512](https://user-images.githubusercontent.com/21364340/35392807-e7322d68-0197-11e8-84bb-b878e78e6529.png)
![screenshot_20180125-210516](https://user-images.githubusercontent.com/21364340/35392809-e7a417fc-0197-11e8-9c62-0d59399b2873.png)
<br>
<u> <b> ADA PERUBUHAN APA? </b> </u> <br>
Untuk mengetahui perubahan apa saja yang terjadi setelah menambahkan kode, mari kita simak PENJELASAN berikut: <br>
<ol>
  <li> Jika saat saya menekan screen layar handphone pada tampilan home saya maka akan muncul seperti Screenshoot ke-1 </li>
  <li> Kemudian tekan atau pilih Widget maka akan muncul dan cari icon seperti tanaman seperti Screenshoot ke-2 </li>
  <li> Tekan dan drag icon pot dan tanaman seperti Screenshoot ke-3 dan letakkan pada tempat yang ditentukan atau yang diinginkan</li>
  <li> Saat dilepaskan atau diletakkan maka akan berubah menjadi icon rumput seperti Screenshoot ke-4</li>
  <li> Kita biasa atur size sesuai yang diinginkan seperti Screenshoot Ke-5</li>
  <li> Dan jika sudah terpasang pada screenhome atau layar utama, maka kita bisa tekan untuk membukanya dengan mudah. Seperti Screenshoot ke-6 </li>
  <li> Jika ditekan tanamannya maka akan muncul seperti Screenshoot ke-7 dan screenshoot ke-8. Dan saat kita menekan atau menyiram tanaman maka Since Watered kembali lagi ke 0 seperti Screenshoot ke-9 </li>
  </ol>
  <br>
  <b> KESIMPULAN PENAMBAHAN KODE ADALAH : AGAR APLIKASI BISA DENGAN MUDAH KITA TEMUI, KITA BISA MEMASANGNYA DI HOMESCREEN DI HANDPHONE DAN TIDAK PERLU MENCARINYA DI MENU. </b>
  <br>
  
## AddWateringService Commit Screenshots
![screenshot_20180125-220631](https://user-images.githubusercontent.com/21364340/35396028-bae31e94-01a0-11e8-800f-66656a2d1ba1.png)
![screenshot_20180125-220644](https://user-images.githubusercontent.com/21364340/35396029-bb2bff74-01a0-11e8-9a0e-cd93376bf0bd.png)
<br>
<u> <b> ADA PERUBUHAN APA? </b> </u> <br>
Untuk mengetahui perubahan apa saja yang terjadi setelah menambahkan kode, mari kita simak PENJELASAN berikut: <br>
<ol>
  <li> Setelah men-debug atau meng-run maka tampilan aplikas di HOMESCREEN akan seperti Screenshoot ke-1. Yang mana sebelum ditambahkan kode icon aplikasi rumput saja, namun setelah ditambahkan kode maka icon aplikasi rumput + air diatasnya. </li>
  <li> Jika dibesarkan maka seperti Screenshoot ke-2 </li>
  </ol>
  <br>
  <b> KESIMPULAN PENAMBAHAN KODE ADALAH : MENAMBAHKAN ICON AIR ATAU IMAGE AIR DIATAS RUMPUT PADA ICON APLIKASI INI </b>
  <br>

## UpdateWidgetsService Commit Screenshots
<br>
<u> <b> ADA PERUBUHAN APA? </b> </u> <br>
Untuk mengetahui perubahan apa saja yang terjadi setelah menambahkan kode, mari kita simak PENJELASAN berikut: <br>
<ol>
  <li> Jika kita tidak menyiram tanaman maka di HOMESCREEN akan muncul tanaman yang akan mati menggantikan icon rumput tadi seperti Screenshoot diatas </li>
  </ol>
  <br>
  <b> KESIMPULAN PENAMBAHAN KODE ADALAH : MENAMBAHKAN MENAMBAHKAN KODE UNTUK MEMUNCULKAN TANAMAN YANG AKAN MATI DI HOMESCREEN YANG MENJADI ICON APLIKASI YANG MENGGANTIKAN ICON RUMPUT TADI </b>
  <br>
  
## Image resources
https://pixabay.com/en/sapling-plant-growing-seedling-154734/
https://pixabay.com/en/cactus-cacti-plant-thorns-spiky-152378/
https://pixabay.com/en/the-background-background-design-352165/
