<div align="center">
  <h1 class="text-align: center;font-weight: bold">Praktikum 1<br>Praktek System Operasi</h1>
  <h3 class="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h3>
</div>
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : </h3>
  <p style="text-align: center;">
    <strong>Dewangga Wahyu Putera Wangsa (3123500007)</strong><br>
    <strong>Hawa Kharisma Zahara (3123500010)</strong><br>
    <strong>Bayu Ariyo Vonda Wicaksono (3122500017)</strong>
  </p>

<h3 style="text-align: center;line-height: 1.5">Politeknik Elektronika Negeri Surabaya<br>Departemen Teknik Informatika Dan Komputer<br>Program Studi Teknik Informatika<br>2023/2024</h3>
  <hr><hr>
</div>


## Daftar Isi
1. [Pendahuluan](#pendahuluan)
2. [Soal](#proses-booting)
3. [Instalisasi](#instalisasi)

## PENDAHULUAN
Sistem operasi (disingkat OS) adalah perangkat lunak fundamental yang mengelola dan mengendalikan semua aspek perangkat, baik perangkat keras maupun perangkat lunak. Ia bertindak sebagai jembatan antara pengguna dan perangkat,

## PROSES BOOTING

### Apa itu booting?
Booting adalah proses yang dilakukan komputer pada saat dinyalakan hingga siap digunakan. Booting berasal dari kata boot yang merupakan singkatan dari bootstrap atau bootstrapping. Bootstrap menggambarkan proses yang secara otomatis memuat dan menjalankan perintah. Selama proses booting ini akan memuat beberapa kode ke dalam memori (RAM) yang diperlukan untuk memulai Windows sehingga siap untuk digunakan.

### Proses terjadinya Booting
1. Menekan Tombol Power On: Saat tombol daya ditekan atau sumber daya lainnya diaktifkan, listrik mengalir ke komponen-komponen perangkat keras komputer.

2. POST (Power-On Self-Test): BIOS (Basic Input/Output System) memulai POST. Ini adalah serangkaian tes yang dilakukan oleh BIOS untuk memeriksa keberadaan dan keadaan komponen-komponen utama seperti CPU, RAM, dan kartu grafis. Jika ada masalah, BIOS akan mengeluarkan peringatan berupa bunyi beep atau kode kesalahan di layar.

3. Inisialisasi Perangkat Keras: Setelah berhasil melewati POST, BIOS akan menginisialisasi perangkat keras lainnya seperti keyboard, mouse, hard disk, dan perangkat penyimpanan lainnya. BIOS juga mengidentifikasi perangkat-perangkat ini dan menentukan cara berkomunikasi dengan mereka.

4. Boot Loader: Setelah semua perangkat keras diinisialisasi, BIOS mencari boot loader yang terletak di lokasi tertentu di media penyimpanan, seperti Master Boot Record (MBR) di hard disk atau EFI System Partition (ESP) pada sistem yang menggunakan UEFI (Unified Extensible Firmware Interface). Boot loader seperti GRUB (Grand Unified Bootloader) atau NTLDR (New Technology Loader) memuat sistem operasi ke dalam memori.

5. Memuat Sistem Operasi: Boot loader memuat kernel dari sistem operasi ke dalam memori. Kernel adalah bagian inti dari sistem operasi yang bertanggung jawab atas manajemen sumber daya perangkat keras, jaringan, dan proses. Setelah kernel dimuat, kontrol diserahkan sepenuhnya kepada sistem operasi.

6. Inisialisasi Sistem Operasi: Sistem operasi melakukan inisialisasi lebih lanjut, termasuk mengaktifkan layanan sistem, memuat driver perangkat keras tambahan, dan menyiapkan lingkungan untuk pengguna.

7. Login: Terakhir, sistem operasi akan menampilkan layar login atau masuk langsung ke desktop, tergantung pada konfigurasi pengguna. Pengguna kemudian dapat memasukkan kredensial mereka untuk mengakses sistem.

8. Setelah proses ini selesai, perangkat siap digunakan oleh pengguna. Proses booting ini biasanya berlangsung dalam waktu beberapa detik hingga beberapa menit, tergantung pada kecepatan perangkat keras dan sistem operasi yang digunakan.

## Instalisasi
### A. Virtual Box
1. Pertama, silakan buka browser di PC Anda.
2. Kemudian akses situs resmi VirtualBox.
   [Virtual Box](https://www.virtualbox.org/)
   ![App Screenshot](img/install_vb/0.png)
3. Kalau sudah, klik Windows host pada kolom VirtualBox 7.0.14 platform packages
   ![App Screenshot](img/install_vb/01.png)
4. Tunggu proses download selesai
5. Buka File Virtual Box 
   ![App Screenshot](img/install_vb/02.png)
6. Selanjutnya pilih tombol Next
   ![App Screenshot](img/install_vb/1.png)
   ![App Screenshot](img/install_vb/2.png)
7. Maka akan muncul notifikasi Warning: Network Interfaces yang menandakan koneksi Anda akan terputus sementara
   ![App Screenshot](img/install_vb/3.png)
8. Pada notifikasi ini, klik Yes untuk melanjutkan proses instalasi
   ![App Screenshot](img/install_vb/4.png)
9. Klik Install untuk memulai proses pemasangan VirtualBox
   ![App Screenshot](img/install_vb/5.png)
10. Tunggu sampai proses instalasi berhasil.
   ![App Screenshot](img/install_vb/6.png)
11. Kalau sudah, lanjut centang opsi Start Oracle VM Virtual Box dan klik tombol Finish untuk membukanya.
   ![App Screenshot](img/install_vb/7.png)
12. Selesai.

### B. Debian
1. Klik "new" untuk membuat virtual machine
   ![App Screenshot](img/install_db/1.png)
2. Create virtual machine dengan mengisi nama, dan iso image. tap checklist dan next
   ![App Screenshot](img/install_db/2.png)
3. Modifikasi  base memory dengan ukuran 4096 Mb dan prosesor dengan ukuran 2 CPU
   ![App Screenshot](img/install_db/3.png)
4. Mengubah ukuran Virtual Hard Disk menjadi 26,50 GB
   ![App Screenshot](img/install_db/64.png)
5. klik Finish <br/>
   ![App Screenshot](img/install_db/4.png) <br/>
6. Klik Start <br/>
   ![App Screenshot](img/install_db/5.png)
7. Pilih Bahasa, disini kami memilih bahasa english <br/>
   ![App Screenshot](img/install_db/6.png)
8. Konfigurasi Lokasi, **Asia** <br/>
   ![App Screenshot](img/install_db/7.png)
9. Konfigurasi Lokasi, **Indonesia** <br/>
   ![App Screenshot](img/install_db/8.png)
10. Konfigurasi wilayah, **United states**
   ![App Screenshot](img/install_db/9.png)
11. konfigurasi Keyboard, **American English**
   ![App Screenshot](img/install_db/10.png)
12. Tunggu Loading hingga selesai
   ![App Screenshot](img/install_db/11.png)
13. Memasukkan Hostname
   ![App Screenshot](img/install_db/12.png)
14. Kosongi domain, klik Continue
   ![App Screenshot](img/install_db/14.png)
15. Setting Password
   ![App Screenshot](img/install_db/15.png)
16. Memasukkan Fullname untuk setup akun
   ![App Screenshot](img/install_db/16.png)
17. Memasukkan Username untuk setup akun
   ![App Screenshot](img/install_db/17.png)
18. Setting Password
   ![App Screenshot](img/install_db/18.png)
19. Konfigurasi Waktu, Western
   ![App Screenshot](img/install_db/19.png)
20. Metode Praktisi, Manual
   ![App Screenshot](img/install_db/20.png)
21. Memilih Praktisi yang ingin dimodifikasi,  **ATA VBOX HARDISK**
   ![App Screenshot](img/install_db/21.png)
22. Pilih Opsi **Yes**, lalu Continue
   ![App Screenshot](img/install_db/22.png)
23. Pilih FREE SPACE, lalu Continue
   ![App Screenshot](img/install_db/23.png)
24. Klik Create a New Partition, lalu Continue
   ![App Screenshot](img/install_db/24.png)
25. Masukkan Size Partisi sebesar 20GB, lalu Continue
   ![App Screenshot](img/install_db/25.png)
26. Pilih Primary, lalu Continue
   ![App Screenshot](img/install_db/26.png)
27. Pilih Beginning, lalu Continue
   ![App Screenshot](img/install_db/27.png)
28. Pilih Done setting up the partition, lalu Continue
   ![App Screenshot](img/install_db/29.png)
29. Pilih FREE SPACE, lalu Continue
   ![App Screenshot](img/install_db/30.png)
30. Klik Create a New Partition, lalu Continue
   ![App Screenshot](img/install_db/31.png)
31. Masukkan Size Partisi sebesar 5GB, lalu Continue
   ![App Screenshot](img/install_db/32.png)
32. Pilih Primary, lalu Continue
   ![App Screenshot](img/install_db/33.png)
33. Pilih Beginning, lalu Continue
   ![App Screenshot](img/install_db/34.png)
34. Klik Mount point, pilih Enter Manually 
   ![App Screenshot](img/install_db/35.png)
35. Ganti menjadi **/storage**
   ![App Screenshot](img/install_db/41.png)
36. Klik Done setting up the partition
   ![App Screenshot](img/install_db/42.png)
37. Pilih FREE SPACE, lalu Continue  
   ![App Screenshot](img/install_db/36.png)
38. Klik Create a New Partition, lalu Continue
   ![App Screenshot](img/install_db/37.png)
39. Masukkan Size Partisi sebesar 1.5GB, lalu Continue
   ![App Screenshot](img/install_db/68.png)
40. Pilih Primary, lalu Continue
   ![App Screenshot](img/install_db/38.png)
41. Pilih Beginning, lalu Continue
   ![App Screenshot](img/install_db/39.png)
42. Klik use as, lalu pilih swap area
   ![App Screenshot](img/install_db/65.png)
43. Klik Done setting up the partition
   ![App Screenshot](img/install_db/40.png)
44. Klik Finish partitioning and write changes to disk
   ![App Screenshot](img/install_db/67.png)
45. Tunggu loading install hingga selesai
   ![App Screenshot](img/install_db/43.png)
46. Pilih No, lalu Continue
   ![App Screenshot](img/install_db/44.png)
47. Pilih packgace manager, indonesia
   ![App Screenshot](img/install_db/45.png)
48. Lalu pilih kebo.pens.ac.id 
   ![App Screenshot](img/install_db/46.png)
49. Http proxy dikosongkan, lalu next
   ![App Screenshot](img/install_db/47.png)
50. Tunggu loading hingga selesai
   ![App Screenshot](img/install_db/48.png)
51. Pilih Yes, lalu Continue
   ![App Screenshot](img/install_db/49.png)
52. Checklist seperti yang tertera digambar bawah ini
   ![App Screenshot](img/install_db/50.png)
53. Tunggu loading instal software
   ![App Screenshot](img/install_db/51.png)
54. Pilih Yes, lalu Continue
   ![App Screenshot](img/install_db/53.png)
55. Pilih sesuai dengan gambar dibawah ini
   ![App Screenshot](img/install_db/54.png)
56. Finish instalisasi
   ![App Screenshot](img/install_db/55.png)
57. Setelah selesai maka tampilan anda akan seperti dibawah ini, linux debian siap digunakan
   ![App Screenshot](img/install_db/56.png)

