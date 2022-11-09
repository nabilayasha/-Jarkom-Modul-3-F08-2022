# Jarkom-Modul-3-F08-2022
David Fischer Simanjuntak - 5025201123 <br/>
Nabila Zakiyah Khansa Machrus	- 5025201139 <br/>
Muhammad Rolanov Wowor - 5025201017 <br/>

## Laporan Resmi Modul 3 F08 2022
![](img/ss.png)

<ul>
<li>Konfigurasi OSTANIA
</ul>

    auto eth0
    iface eth0 inet dhcp

    auto eth1
    iface eth1 inet static
	address 192.203.1.1
	netmask 255.255.255.0

    auto eth2
    iface eth2 inet static
	address 192.203.2.1
	netmask 255.255.255.0

    auto eth3
    iface eth3 inet static
	address 192.203.3.1
	netmask 255.255.255.0

<ul>
<li>Konfigurasi SSS & Garden
</ul>

    auto eth0
    iface eth0 inet dhcp

<ul>
<li>Konfigurasi WISE
</ul>

    auto eth0
    iface eth0 inet static
	address 192.203.2.2
	netmask 255.255.255.0
	gateway 192.203.2.1

<ul>
<li>Konfigurasi BERLINT
</ul>

    auto eth0
    iface eth0 inet static
	address 192.203.2.3
	netmask 255.255.255.0
	gateway 192.203.2.1

<ul>
<li>Konfigurasi WESTALIS
</ul>

    auto eth0
    iface eth0 inet static
	address 192.203.2.4
	netmask 255.255.255.0
	gateway 192.203.2.1

<ul>
<li>Konfigurasi EDEN
</ul>



<ul>
<li>Konfigurasi NEWSTON CASTLE
</ul>

<ul>
<li>Konfigurasi KEMONO PARK 
</ul>

### **Soal 1**
Semua client yang ada HARUS menggunakan konfigurasi IP dari DHCP Server

### **Jawaban**

### **Soal 2**
Client yang melalui Switch1 mendapatkan range IP dari [prefix IP].1 .50 - [prefix IP].1 .88
dan [prefix IP].1 .1 20 - [prefix IP].1 .1 55 

### **Jawaban**

### **Soal 3**
Client yang melalui Switch3 mendapatkan range IP dari [prefix IP].3.1 0 - [prefix IP].3.30
dan [prefix IP].3.60 - [prefix IP].3.85 

### **Jawaban**

### **Soal 4**
Client mendapatkan DNS dari WISE dan client dapat terhubung dengan internet melalui
DNS tersebut

### **Jawaban**

### **Soal 5**
Lama waktu DHCP server meminjamkan alamat IP kepada Client yang melalui Switch1
selama 5 menit sedangkan pada client yang melalui Switch3 selama 1 0 menit. Dengan
waktu maksimal yang dialokasikan untuk peminjaman alamat IP selama 11 5 menit. 

### **Jawaban**

### **Soal 6**
Loid dan Franky berencana menjadikan Eden sebagai server untuk pertukaran informasi dengan
alamat IP yang tetap dengan IP [prefix IP].3.13 

### **Jawaban**

### **Soal 7**
SSS, Garden, dan Eden digunakan sebagai
client Proxy agar pertukaran informasi dapat terjamin keamanannya, juga untuk mencegah
kebocoran data

### **Jawaban**
