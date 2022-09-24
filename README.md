# Laporan Resmi Modul 1
Repository ini dibuat sebagai laporan resmi untuk pengerjaan [Soal Shift Modul 1](https://docs.google.com/document/d/1e5fXdleV59vFthVeK0O5WfmuOYV6xi6WkpHsZEiBofE/edit) dari praktikum Mata Kuliah Komunikasi Data dan Jaringan Komputer.

Repository ini dibuat oleh:  

**Kelompok ITB06**
- Sarah Hanifah Pontoh	5027201006
- Sharira Saniane 	5027201016
- Naufal Dhiya Ulhaq 	5027201029


## Table of Contents

## Files
Pada soal shift ini, kami diberikan tiga buah file yaitu:  
[soal1-2.pcapng](https://drive.google.com/file/d/1ys_8z-ggXnAFC9Pztaw_2MDpf1QfKUZX/view?usp=sharing)    
[soal3-6.pcapng](https://drive.google.com/file/d/1T-8AzH97Z6xmWpKk7ptwIIIOzWnXq6ij/view?usp=sharing)  
[soal8-10.pcapng](https://drive.google.com/file/d/1auVHDMKHhpbDLwRyN_cmPW7x4sL-a_fy/view?usp=sharing)  

Dengan file-file tersebut, kami diberikan beberapa soal:

## Soal 1
Sebutkan web server yang digunakan pada "monta.if.its.ac.id"!  
  
Langkah-langkah : 
1. Memasukkan Filter : `http.host==monta.if.its.ac.id`

![Image 1.1](Photos/1.1.png)

2. Follow salah satu paket yang dikirimkan.

![Image 1.2](Photos/1.2.png)

3. Pada paket yang sudah difollow, kita dapat mencari web server yang digunakan pada "monta.if.its.ac.id" yaitu : `nginx/1.10.3`.

![Image 1.3](Photos/1.3.png)

## Soal 2
Ishaq sedang bingung mencari topik ta untuk semester ini , lalu ia datang ke website monta dan menemukan detail topik pada website “monta.if.its.ac.id” , judul TA apa yang dibuka oleh ishaq ?  

Langkah-langkah : 
1. Memasukkan Filter : `http.host==monta.if.its.ac.id`
2. Memfollow paket http yang terdapat `detailTopik` pada url nya.

![Image 2.1](Photos/2.1.png)

3. Dari paket tersebut, kita dapat menemukan judul topik yang dicari adalah: `Evaluasi unjuk kerja User Space Filesystem (FUSE)`.

![Image 2.2](Photos/2.2.png)

## Soal 3
Filter sehingga wireshark hanya menampilkan paket yang menuju port 80!  

Langkah-langkah :  
1. Membuka file [soal3-6.pcapng](https://drive.google.com/file/d/1T-8AzH97Z6xmWpKk7ptwIIIOzWnXq6ij/view?usp=sharing).
2. Memasukkan filter : `tcp.dstport == 80 || udp.dstport==80`

![Image 3.1](Photos/3.1.png)

## Soal 4
Filter sehingga wireshark hanya mengambil paket yang berasal dari port 21!  

Langkah-langkah : 
1. Membuka file [soal3-6.pcapng](https://drive.google.com/file/d/1T-8AzH97Z6xmWpKk7ptwIIIOzWnXq6ij/view?usp=sharing).
2. Memasukkan filter: `tcp.dstport == 21 || udp.dstport==21`

![Image 4.1](Photos/4.1.png)

## Soal 5
Filter sehingga wireshark hanya mengambil paket yang berasal dari port 443!  

Langkah-langkah : 
1. Membuka file [soal3-6.pcapng](https://drive.google.com/file/d/1T-8AzH97Z6xmWpKk7ptwIIIOzWnXq6ij/view?usp=sharing).
2. Memasukkan filter :  `tcp.dstport == 443 || udp.dstport == 443`

![Image 5.1](Photos/5.1.png)

## Soal 6
Filter sehingga wireshark hanya menampilkan paket yang menuju ke lipi.go.id!  

Langkah-langkah : 
1. Membuka file [soal3-6.pcapng](https://drive.google.com/file/d/1T-8AzH97Z6xmWpKk7ptwIIIOzWnXq6ij/view?usp=sharing).
2.  Memasukkan filter :  `http.host == lipi.go.id`

![Image 1.1](Photos/1.1.png)

## Soal 7
Filter sehingga wireshark hanya mengambil paket yang berasal dari ip kalian!

Langkah-langkah : 
1. Filter => ip.src == 192.168.0.108

![Image 1.1](Photos/7.1.png)

## Soal 8
Telusuri aliran paket dalam file .pcap yang diberikan, cari informasi berguna berupa percakapan antara dua mahasiswa terkait tindakan kecurangan pada kegiatan praktikum. Percakapan tersebut dilaporkan menggunakan protokol jaringan dengan tingkat keandalan yang tinggi dalam pertukaran datanya sehingga kalian perlu menerapkan filter dengan protokol yang tersebut.  

Langkah-langkah:
1. Membuka file [soal3-6.pcapng](https://drive.google.com/file/d/1T-8AzH97Z6xmWpKk7ptwIIIOzWnXq6ij/view?usp=sharing).

## Soal 9
Terdapat laporan adanya pertukaran file yang dilakukan oleh kedua mahasiswa dalam percakapan yang diperoleh, carilah file yang dimaksud! Untuk memudahkan laporan kepada atasan, beri nama file yang ditemukan dengan format [nama_kelompok].des3 dan simpan output file dengan nama “flag.txt”.

Langkah-langkah:
1. 

## Soal 10
Temukan password rahasia (flag) dari organisasi bawah tanah yang disebutkan di atas!

Langkah-langkah:
1. 
