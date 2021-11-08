# UML : APLIKASI SECHEDULE MANAGER

## Use Case Diagram : 

Pada Use Diagram ini terdapat 2 Aktor yaitu User dan Database yang di mana aktor tersebut mempunyai beberapa kegiatan yaitu Login ( terdapat jg Daftar dan Lupa Password ), Manage Jadwal ( Tambah Jadwal, Edit Jadwal, Hapus Jadwal ), dan Ganti Password.
    
![Aplikasi Schedule Manager](https://user-images.githubusercontent.com/31654976/140764560-c552ee28-7e71-4efb-afd8-bdfcd25e0d0d.jpeg)

## Activity Diagram :

1. Form Login
  
Pada Activity Diagram ini dijelaskan bahwa user dapat membuka aplikasi kemudian aplikasi menampilkan form logi, kemudian terdapat pilihan jika user memiliki akun maka user akan membuat akun terlebih dahulu, kemudian jika user sudah memiliki akun maka user akan memasukkan username dan password kemudian aplikasi akan memverifikasi apakah user dan password yang dimasukkan sudah benar, dan jika benar maka Aplikasi akan menampilkan tampilan Aplikasi.

![Activity Diagram - Form Login](https://user-images.githubusercontent.com/31654976/140766487-132cdb13-0f0a-4ee8-8939-3d664ef25e21.jpeg)

2. Tambah Jadwal

Pada Activity Diagram ini User pertama kali akan memilih Icon Tambah Jadwal jika ingin menambah jadwal kemudian aplikasi akan menampilkan kategori kemudian user akan memilih kategori sesuai dengan jadwal yang diinginkan kemudian aplikasi menampilkan form input jadwal kemudian user akan input data - data yang diminta oleh aplikasi kemudian user akan memvalidasi data tersebut jika sudah sesuai maka user akan memilih save kemudian aplikasi akan menampilkan tampilan awal aplikasi.

![Tambah Jawal](https://user-images.githubusercontent.com/31654976/140769621-225d8da3-0189-402a-a374-afd949c51010.jpeg)

3. Edit Jadwal

Pada Activity Diagram ini User pertama kali akan memilih icon tanggal jadwal yang mau diedit kemudian aplikasi akan menampilkan daftar jadwal sesuai dengan tanggal yang dipilih kemudian User memilih jadwal yang mau diedit kemudian aplikasi akan menampilkan deskripsi jadwal yang dipilih kemudian User akan memilih Icon Edit kemudian Aplikasi akan menampilkan Form Edit Jadwal kemudian User akan Input Data - Data yang mau diedit kemudian user akan memvalidasi apakah yang diinputkan sudah sesuai jika sesuai maka aplikasi kembali ke tampilan awal jika tidak maka user kemabali menginputkan data yang sesuai.

![Edit Jawal](https://user-images.githubusercontent.com/31654976/140770982-738523c0-f1b8-4241-8a85-e74b1512db3d.jpeg)

4. Hapus Jadwal 

Pada Activity Diagram ini User pertama kali akan memilih tanggal jadwal yang mau dihapus kemudian aplikasi akan menampilkan dafatr jadwal pada tanggal yang dipilih kemudian User akan memilih jadwal yang mau dihapus kemudian aplikasi akan menampilkan deskripsi jadwal yang dipilih kemudian User akan memilih Setting yang dimana ditandai dengan titik tiga kemudian user akan memilih hapus untuk menghapus jadwal kemudian User akan melakukan verify apakah User yakin untuk menghapus jadwal tersebut jika tidak maka aplikasi akan menampilkan kembali pada deskripsi jadwal yang dipilih dan jika iya maka aplikasi akan mengahapus jadwal kemudian aplikasi akan menampilkan kembali tampilan awal aplikasi.

![Hapus Jadwal](https://user-images.githubusercontent.com/31654976/140771793-ddd96d70-88d5-4630-9104-29d1d943177c.jpeg)

## Sequence Diagram

Pada Sequence diagram ditunjukkanurutan jalannya sebuah sistem yang dirancang. Proses ini dimulai dari User melakukan Isi data diri pada Form Register kemdudian User akan mendaftar pada aplikasi kemduian data user akan dikirim untuk di simpan di database kemduian database melakukan validasi jika validasi berhasil maka data berhasil disimpan, kemudian user akan melakukan login dengan cara isi email dan password kemudian data user akan dikirim ke database untuk divalidasi kemudian apliaksi akan menampilkan menu aplikasi, kemudian user memilih menu kemudian user memilih form acara kemuidan aplikasi akan meminta user untuk mengisi form acara kemudian user akan menginputkan data pada form acara kemudian data acara user akan dikirim ke database untuk divalidasi kemudian database akan menyampaikan informasi data berhasil disimpan.

![Register drawio](https://user-images.githubusercontent.com/31654976/140774164-49b91740-b91d-4545-845c-51357fcdd54d.png)

![Login drawio](https://user-images.githubusercontent.com/31654976/140774190-7d238cfb-9ed1-4083-bbae-2f5580601d42.png)

![isi-form](https://user-images.githubusercontent.com/31654976/140774211-d3b86f0f-739e-4b15-80d4-d1229b565978.jpg)
