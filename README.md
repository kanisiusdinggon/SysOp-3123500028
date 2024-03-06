<div align="center">
  <h1 style="text-align: center;font-weight: bold">PRAKTIKUM 1<br>SISTEM OPERASI</h1>
  <h4 style="text-align: center;">Dosen Pengampu : Dr. Ferry Astika Saputra, S.T., M.Sc.</h4>
</div>
<br />
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/id/4/44/Logo_PENS.png" alt="Logo PENS">
  <h3 style="text-align: center;">Disusun Oleh : </h3>
  <p style="text-align: center;">
    <strong>Marieta Nona Alfani (312350026) </strong><br>
    <strong>Ale Perdana Putra Darmawan (3123500027) </strong><br>
    <strong>Kanisius Keru Okok Dinggon(3123500028)</strong>
  </p>
<h3 style="text-align: center;line-height: 1.5">Politeknik Elektronika Negeri Surabaya<br>Departemen Teknik Informatika Dan Komputer<br>Program Studi Teknik Informatika<br>2023/2024</h3>
  <hr><hr>
</div>

## Daftar Isi
1. [Dasar Teori](#Dasar-teori)
2. [Soal](#soal)
3. [Instalasi Oracle Virtual Box]

## Dasar teori
Pengertian Sistem Operasi:</br>
<strong>Sistem Operasi</strong> adalah perangkat lunak pada lapisan pertama yang ditempatkan pada memori komputer pada saat komputer dinyalakan booting. Sedangkan software-software lainnya dijalankan setelah sistem operasi berjalan, dan sistem operasi akan melakukan layanan inti untuk software-software itu.

## Soal
#### Sebutkan dan jelaskan proses booting !
1 . <strong>Power ON</strong>
Saat tombol power atau tombol reset dihidupkan, sumber daya listrik akan mengalir ke komputer.
Kemudian, perangkat keras akan menerima daya untuk dinyalakan.

2 . <strong>POST (Power On Selft Test)</strong>
Setelah dinyalakan, komputer akan melakukan Power-On Self-Test atau POST, yang merupakan serangkaian tes perangkat keras untuk memastikan bahwa semuanya berfungsi dengan baik. 
POST akan memeriksa RAM, prosesor, kartu grafis, dan perangkat keras lainnya. 

3 . <strong>Inisialisasi perangkat keras</strong>
Setelah POST selesai, komputer akan menginisialisasi perangkat keras seperti hard drive, keyboard, mouse, dan perangkat lainnya. 
Proses ini melibatkan tahap mengenali perangkat keras, memuat driver yang diperlukan, dan menyiapkan perangkat untuk digunakan.

4 . <strong>Membaca sektor boot</strong>
Selanjutnya, komputer akan mencari sektor boot di hard drive atau perangkat penyimpanan lainnya. 
Sektor boot adalah area khusus yang berisi instruksi awal untuk memuat sistem operasi.

5 . <strong>Memuat Sistem Operasi</strong>
Setelah sektor boot ditemukan, komputer akan memuat sistem operasi ke dalam memori utama (RAM). 
Kemudian, sistem operasi akan mengambil alih kendali dan mulai menjalankan program-program yang diperlukan untuk mengoperasikan komputer.

#### Bagaimana cara install Oracle Virtual Box dan Debian dalam Virtual Box ?

## Instalasi Oracle Virtual Box
1. Masuk ke laman [Oracle Virtual box](https://www.virtualbox.org/wiki/Downloads), lalu unduh sesuai sistem operasi yang anda gunakan.
![ss](ss/01.jpeg)

2. Masuk ke laman Download sistem operasi [Debian](https://www.debian.org/download) untuk mengunduh sistem operasi Linux Debian.
   ![ss](ss/20.png)

3. Buka setup Oracle dan klik Next.
   ![ss](ss/21.jpeg)

4. Dalam menu tidak ada yang perlu diubah, klik Next.
   ![ss](ss/22.jpeg)

5. Klik Yes.
   ![ss](ss/23.jpeg)

6. Klik Install.
   ![ss](ss/24.jpeg)

7. Oracle Virtual Box telah di install, klik finish.
   ![ss](ss/25.jpeg)

## Instalasi Linux Debian dalam Oracle Virtual Box
1. Buka Oracle Virtual Box, lalu klik opsi "New".
![ss](ss/06.jpeg)

2. Isi nama, pilih letak penyimpanan Virtual Box, masukkan file ISO debian yang telah diunduh, klik "Skip unattended Installation, dan klik Next.
   ![ss](ss/07.jpeg)

3. Isi Username dan hostname dan ubah password, untuk domain name tidak perlu diganti, lalu klik Next. 
   ![ss](ss/11.jpeg)

4. Tentukan RAM dan jumlah CPU yang diinginkan, lalu klik Next.
   ![ss](ss/05.jpeg)

5. Tentukan ukuran storage didalam Virtual Machine, lalu klik Next.
   ![ss](ss/10.jpeg)

6. Dalam tampilan ini, anda dapat melihat ulang pilihan yang anda telah pilih sebelumnya, jika sudah sesuai keinginan, pilih Finish.
   ![ss](ss/13.jpeg)

## Mengkonfigurasi Debian dalam Oracle Virtual Box
1. Klik "Start" untuk membuka Virtual Machine.
![ss](ss/12.jpeg)

2. Pilih Graphical Install untuk memulai konfigurasi Debian.
   ![ss](ss/15.jpeg)

3. Pilih Bahasa, lalu klik continue.
   ![ss](ss/14.jpeg)

4. Pilih lokasi, lalu klik continue.
   ![ss](ss/17.jpeg)

5. Pilih konfigurasi bahasa Keyboard, lalu klik continue.
   ![ss](ss/18.jpeg)

6. Isi Hostname, lalu klik continue.
   ![ss](ss/19.png)

7. Untuk nama domain tidak perlu diisi, klik continue.
   ![26.png](/26.png)

9. Isi root password, lalu klik continue.
   ![27.png](/27.png)

10. Isi nama, lalu klik continue.
    ![28.png](/28.png)

11. Isi username, lalu klik continue.
    ![29.png](/29.png)

12. Pilih lokasi jam, lalu klik continue.
    ![30.png](/30.png)

13. Untuk partition disk, pilih manual, lalu klik continue.
    ![31.png](/31.png)

14. Pilih opsi seperti pada gambar dibawah, lalu klik continue.
    ![ss](ss/32.png)

15. Pilih "Yes" untuk membuat partition disk baru, lalu klik continue.
    ![ss](ss/33.png)

16. Pilih pri/log untuk membuat bagian partition disk, lalu klik continue.
    ![ss](ss/34.png)


17. Pilih "create new partition disk" untuk membuat partition disk, lalu klik continue.
    ![ss](ss/35.png)

18. Tentukan jumlah penyimpanan partition disk pertama, lalu klik continue.
    ![ss](ss/36.png)

19. Pilih "primary" agar menjadikan penyimpanan utama, lalu klik continue.
    ![ss](ss/37.png)

20. Pilih "beginning", lalu klik continue.
    ![ss](ss/38.png)


21. pilih opsi "done setting up the partition" klik continue.
    ![ss](ss/39.png)

22. Setelah membuat partition disk pertama, silahkan membuat partition disk ke dua, tentukan isi penyimpanan yang ukurannya lebih kecil dibandingkan partition disk pertama, lalu klik continue.
    ![ss](ss/40.png)


23. Untuk partition disk kedua, pilih opsi logical dan pada mount point pilih Enter manually dan ketik "/storage", lalu klik continue.
    ![ss](ss/41.png)

24. Setelah membuat partition disk kedua, silahkan membuat partition disk ke tiga, tentukan isi penyimpanan yang ukurannya lebih kecil dibandingkan partition disk kedua, lalu klik continue.
    ![ss](ss/42.png)

25. Untuk partition disk kedua, pilih opsi logical, lalu jadikan "swap area" pada bagian "use as:", lalu klik continue.
    ![ss](ss/43.png)

26. Cek ulang seperti gambar dibawah, jika sudah sesuai, klik continue.
    ![ss](ss/44.png)
    
28. Pilih opsi "Yes", lalu klik continue.
    ![ss](ss/45.png)

29. Pilih opsi "no", lalu klik continue.
    ![ss](ss/46.png)

30. Pilih lokasi terdekat untuk mengunduh package manager, lalu klik continue.
    ![ss](ss/47.png)

31. Pilih archive mirror, lalu klik continue.
    ![ss](ss/48.png)
    
33. Pada bagian ini tidak perlu diisi, klik continue
    ![ss](ss/49.png)

35. Pilih opsi "Yes", lalu klik continue.
    ![ss](ss/50.png)

37. Pilih opsi "/dev/sda", lalu klik continue.
    ![ss](ss/51.png)
    
39. Instalasi dan konfigurasi Debian telah selesai, klik continue dan Virtual machine akan me-reboot. 
    ![ss](ss/52.png)
    
41. Tampilan Linux Debian setelah reboot.
    ![ss](ss/53.png)
<!---
kanisiusdinggon/kanisiusdinggon is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
