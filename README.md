# Jarkom-Modul-1-I08-2023

Nama Anggota | NRP
------------------- | --------------		
Mardhatillah Shevy Ananti | 5025211070
Kirana Alivia Enrico | 5025211190

## List of Contents :
- [Soal 1](#soal-1)
- [Soal 2](#soal-2)
- [Soal 3](#soal-3)
- [Soal 4](#soal-4)
- [Soal 5](#soal-5)
- [Soal 6](#soal-6)
- [Soal 7](#soal-7)
- [Soal 8](#soal-8)
- [Soal 9](#soal-9)
- [Soal 10](#soal-10)

## Soal 1
User melakukan berbagai aktivitas dengan menggunakan protokol FTP. Salah satunya adalah mengunggah suatu file.
- Berapakah sequence number (raw) pada packet yang menunjukkan aktivitas tersebut? 
- Berapakah acknowledge number (raw) pada packet yang menunjukkan aktivitas tersebut? 
- Berapakah sequence number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?
- Berapakah acknowledge number (raw) pada packet yang menunjukkan response dari aktivitas tersebut?

## Answer : 
- `258040667`
- `1044861039`
- `1044861039`
- `258040696`

## Explanation :
<img src="./img/1a.png" width="500">
<img src="./img/1b.png" width="500">


---


## Soal 2 
(REVISI) Sebutkan web server yang digunakan pada portal praktikum Jaringan Komputer!

## Answer : 
`gunicorn`

## Explanation :
<img src="./img/2.png" width="500">


---


## Soal 3
Dapin sedang belajar analisis jaringan. Bantulah Dapin untuk mengerjakan soal berikut:
Berapa banyak paket yang tercapture dengan IP source maupun destination address adalah 239.255.255.250 dengan port 3702?
Protokol layer transport apa yang digunakan?

## Answer : 
- `21 paket`
- `UDP`

## Explanation :
<img src="./img/3.png" width="500">


---


## Soal 4
Berapa nilai checksum yang didapat dari header pada paket nomor 130?

## Answer : 
`0x18e5`

## Explanation :

<img src="./img/4.png" width="500">


---


## Soal 5 
(REVISI) Elshe menemukan suatu file packet capture yang menarik. Bantulah Elshe untuk menganalisis file packet capture tersebut.
- Berapa banyak packet yang berhasil di capture dari file pcap tersebut?
- Port berapakah pada server yang digunakan untuk service SMTP?
- Dari semua alamat IP yang tercapture, IP berapakah yang merupakan public IP?

## Answer : 
- `60`
- `25`
- `74.53.140.153`

## Explanation :

<img src="./img/5a.png" width="500">
<img src="./img/5b.png" width="500">
<img src="./img/5c.png" width="500">
<img src="./img/5d.png" width="500">
<img src="./img/5e.png" width="500">
<img src="./img/5f.png" width="500">


---


## Soal 6 
(REVISI) Seorang anak bernama Udin Berteman dengan SlameT yang merupakan seorang penggemar film detektif. sebagai teman yang baik, Ia selalu mengajak slamet untuk bermain valoranT bersama. suatu malam, terjadi sebuah hal yang tak terdUga. ketika udin mereka membuka game tersebut, laptop udin menunjukkan sebuah field text dan Sebuah kode Invalid bertuliskan "server SOURCE ADDRESS 7812 is invalid". ketika ditelusuri di google, hasil pencarian hanya menampilkan a1 e5 u21. jiwa detektif slamet pun bergejolak. bantulah udin dan slamet untuk menemukan solusi kode error tersebut.

## Answer : 
`JDRNJA`

## Explanation :

<img src="./img/6a.png" width="500">
<img src="./img/6b.png" width="500">


---


## Soal 7
Berapa jumlah packet yang menuju IP 184.87.193.88?

## Answer : 
`6`

## Explanation :

<img src="./img/7.png" width="500">


---


## Soal 8
(REVISI) Berikan kueri filter sehingga wireshark hanya mengambil semua protokol paket yang menuju port 80! (Jika terdapat lebih dari 1 port, maka urutkan sesuai dengan abjad)

## Answer : 
`tcp.dstport == 80 || udp.dstport == 80`

## Explanation :

<img src="./img/8.png" width="500">


---


## Soal 9
(REVISI) Berikan kueri filter sehingga wireshark hanya mengambil paket yang berasal dari alamat 10.51.40.1 tetapi tidak menuju ke alamat 10.39.55.34!

## Answer : 
`ip.src == 10.51.40.1 && ip.dst != 10.39.55.34`

## Explanation :
At the top of the Wireshark window labeled "Display Filter, we typed the following query filter that requests Wireshark to display only packets with the source IP address (ip.src) of 10.51.40.1 and not the destination IP address (ip.dst) of 10.39.55.34.

<img src="./img/9.png" width="500">

Wireshark will only display packets originating from the IP address 10.51.40.1 and not going to the IP address 10.39.55.34.


---


## Soal 10
(REVISI) Sebutkan kredensial yang benar ketika user mencoba login menggunakan Telnet

## Answer : 
`dhafin:kesayangannyak0k0`

## Explanation :

<img src="./img/10a.png" width="500">
<img src="./img/10b.png" width="500">
<img src="./img/10c.png" width="500">


---
