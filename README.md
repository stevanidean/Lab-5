# PEMROGRAMAN WEB 2 - PRAKTIKUM 5 
 #BIODATA 
 NAMA : STEVANI DEAN SAFIRA
 KELAS : TI.21.A.2
 NIM : 312110463
 
 # LANGKAH LANGKAH
 1. Buat folder baru dengan nama Lab_php_oop
 2. buat file baru dengan nama mobil.php lalu masukan kode berikut
 
 <?php
/**
* Program sederhana pendefinisian class dan pemanggilan class.
**/
class Mobil
{
private $warna;
private $merk;
private $harga;
public function __construct()
{
$this->warna = "Biru";
$this->merk = "BMW";
$this->harga = "10000000";
}
public function gantiWarna ($warnaBaru)
{
$this->warna = $warnaBaru;
}
public function tampilWarna ()
{
echo "Warna mobilnya : " . $this->warna;
}
}
// membuat objek mobil
$a = new Mobil();
$b = new Mobil();
// memanggil objek
echo "<b>Mobil pertama</b><br>";
$a->tampilWarna();
echo "<br>Mobil pertama ganti warna<br>";
$a->gantiWarna("Merah");
$a->tampilWarna();
// memanggil objek
echo "<br><b>Mobil kedua</b><br>";
$b->gantiWarna("Hijau");
$b->tampilWarna();
?>

![Capture](https://user-images.githubusercontent.com/92729505/232796665-7290c8c0-9148-4525-8384-e8d020850485.PNG)

setelah itu saya gatau lagi pak buat gabungin dari praktikum sebelumnya
![vailed](https://user-images.githubusercontent.com/92729505/232796871-a99c5a08-4d92-4517-aac0-069977bcccb8.PNG)


