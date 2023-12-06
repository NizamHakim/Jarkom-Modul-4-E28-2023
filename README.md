# Jarkom-Modul-4-E28-2023

## Kelompok E28
- Shafa Nabilah Hanin / 5025211222
- Nizam Hakim Santoso / 5025211209

# Lapres Praktikum 4
## Daftar Isi
- [CPT / CIDR]()
    - [Topologi]()
    - [Merging Subnet]()
    - [Subnet Tree]()
    - [Spreadsheet Subnet]()
    - [Testing]()
- [GNS3 / VLSM]()
    - [Topologi]()
    - [Subnet Tree]()
    - [Testing]()

## CPT / CIDR
### Topologi
Penamaan subnet yang kami gunakan untuk topologi metode CIDR adalah sebagai berikut:  

![topologi-cidr](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/83547f05-884e-467f-86e0-935b1a01295b)

### Merging Subnet
Langkah-langkah penggabungan subnet untuk menentukan subnet terbesar kami jabarkan pada canva seperti berikut:

![Merging_1](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/4ef4e4bf-8c29-4bef-874e-72cdfae8e981)  

![Merging-Table-1](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/4a372be4-a352-44e6-b34f-4cda66d17c57)  

![Merging_2](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/6f902079-695a-421a-bd22-ee0e4a70d219)  

![Merging-Table-2](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/ab02a322-6741-475a-a9ae-ea19ee653415)  

![Merging_3](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/bc9e1c82-cb4a-4579-b1fd-5857b037d0b0)  

![Merging-Table-3](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/db7b7b01-1538-4a20-bbd0-3862ee041547)  

![Merging_4](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/c545301d-96d8-43c6-b02a-cc4ff3d36320)  

![Merging-Table-4](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/21ee1254-7538-4612-8feb-235d89029e94)  

![Merging_5](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/c13ce867-e0db-429a-aeef-fa0d2ec84cee)  

![Merging-Table-5](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/e4b8d5a3-ebb5-485e-a74a-a3602c8e3591)  

![Merging_6](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/c7bb0f3c-de04-4aa8-9076-1f94565969d5)  

![Merging-Table-6](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/4e34db24-b4da-4574-b3b2-aa9e9fca08c8)  

![Merging_7](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/50c47828-788c-4cef-bf9f-df8ffd9c354e)  

![Merging-Table-7](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/fad21233-2771-4774-954b-3303abb4ba65)  

![Merging_8](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/65000082-5cc7-4992-9d05-1ce1a05f5688)  

![Merging-Table-8](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/563f5fa9-172e-41ad-81b6-f36d7e0c9d89)  

![Merging_9](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/6c4a5a83-3b3a-449c-97b8-593cd7404725)  

didapatkan length tertinggi /14

Dokumen lengkap ada di: [Canva](https://www.canva.com/design/DAF1klu-Ybg/hjfjVTfJBfJlFuXL9a1-SQ/edit?utm_content=DAF1klu-Ybg&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton) dan [Spreadsheet](https://docs.google.com/spreadsheets/d/1EBKF3tDHpHjzHjmlIIN7Yl3tEOGVCPE1RmuB9RrNEj8/edit?usp=sharing)

### Subnet Tree
Setelah merging kembalikan subnet-subnet sesuai dengan length awalnya dengan tree sebagai berikut:

![CIDR_Tree](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/a6b3caa0-7ddc-42eb-b06e-6cac1b365f0c)

Dokumen lengkap ada di: [Canva](https://www.canva.com/design/DAF1tzOU0JI/D065NM6o1WV48q73KsWPQQ/edit?utm_content=DAF1tzOU0JI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

### Spreadsheet Subnet
Data kelengkapan IP dipetakan dalam spreadsheet sebagai berikut:

![IP-Lengkap](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/fc2be9af-30b3-4b74-a097-4b1d232a4073)

Connection pair untuk tiap-tiap router dipetakan dalam spreadsheet sebagai berikut:

![Connection-Pair](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/561b8de1-eb71-4c4d-be14-2812d0efcb20)

Dokumen lengkap ada di: [Spreadsheet](https://docs.google.com/spreadsheets/d/1EBKF3tDHpHjzHjmlIIN7Yl3tEOGVCPE1RmuB9RrNEj8/edit?usp=sharing)

### Testing
Lakukan testing dengan melakukan beberapa ping seperti berikut dalam mode simulasi.

![start-test](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/b30f0cb7-d7ce-46a3-97f1-29fa20a209ec)

![Testing](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/5f399f8d-a885-4799-b98a-54ab59da85e5)

Hasil:

![end-test](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/5d51a641-4386-460f-b467-086daf5ccf4e)

## GNS3 / VLSM
### Topologi
![topologi](img/topologi_vlsm.png)

![topologi2](img/vlsm-gns3.png)

### Subnet Tree
![subnet tree](img/tree-vlsm.jpg)

![](img/rute_vlsm.png)

![](img/ip_vlsm.png)

### Configuration
## Network Configuration
Aura

```
auto lo
iface lo inet loopback

auto eth0
iface eth0 inet dhcp

#A8
auto eth1
iface eth1 inet static
address 192.220.24.148
netmask 255.255.255.252

#A12
auto eth2
iface eth2 inet static
address 192.220.24.112
netmask 255.255.255.252

#A13
auto eth3
iface eth3 inet static
address 192.220.24.116
netmask 255.255.255.252

```

Denken

```
auto lo
iface lo inet loopback

#A12
auto eth0
iface eth0 inet static
address 192.220.24.112
netmask 255.255.255.252
gateway 192.220.24.113

#A19
auto eth1
iface eth1 inet static
address 192.220.23.0
netmask 255.255.255.0

```

Frieren

```
auto lo
iface lo inet loopback

#A8
auto eth0
iface eth0 inet static
address 192.220.24.148
netmask 255.255.255.252
gateway 192.220.24.150

#A6
auto eth1
iface eth1 inet static
address 192.220.24.144
netmask 255.255.255.252

#A7
auto eth2
iface eth2 inet static
address 192.220.24.64
netmask 255.255.255.224
```

Fern

```
auto lo
iface lo inet loopback

#A3
auto eth0
iface eth0 inet static
address 192.220.24.136
netmask 255.255.255.252
gateway 192.220.24.138

#A1
auto eth1
iface eth1 inet static
address 192.220.0.0
netmask 255.255.248.0
```

Flamme

```
auto lo
iface lo inet loopback

#A6
auto eth0
iface eth0 inet static
address 192.220.24.144
netmask 255.255.255.252
gateway 192.220.24.146

#A3
auto eth1
iface eth1 inet static
address 192.220.24.136
netmask 255.255.255.252

#A2
auto eth2
iface eth2 inet static
address 192.220.8.0
netmask 255.255.252.0

#A4
auto eth3
iface eth3 inet static
address 192.220.24.140
netmask 255.255.255.252
```

Himmel

```
auto lo
iface lo inet loopback

#A44
auto eth0
iface eth0 inet static
address 192.220.24.140
netmask 255.255.255.252
gateway 192.220.24.143

#A5
auto eth1
iface eth1 inet static
address 192.220.24.96
netmask 255.255.255.248
```

Eisen

```
auto lo
iface lo inet loopback

#A13
auto eth0
iface eth0 inet static
address 192.220.24.116
netmask 255.255.255.252
gateway 192.220.24.119

#A9
auto eth1
iface eth1 inet static
address 192.220.24.104
netmask 255.255.255.248

#A14
auto eth2
iface eth2 inet static
address 192.220.24.120
netmask 255.255.255.252

#A18
auto eth3
iface eth3 inet static
address 192.220.24.132
netmask 255.255.255.252

#A17
auto eth4
iface eth4 inet static
address 192.220.24.128
netmask 255.255.255.252
```

Lugner

```
auto lo
iface lo inet loopback

#A18
auto eth0
iface eth0 inet static
address 192.220.24.132
netmask 255.255.255.252
gateway 192.220.24.134

#A21
auto eth1
iface eth1 inet static
address 192.220.22.0
netmask 255.255.255.0

#A20
auto eth2
iface eth2 inet static
address192.220.12.0
netmask 255.255.252.0
```

Lawine

```
auto lo
iface lo inet loopback

#A15
auto eth0
iface eth0 inet static
address 192.220.24.124
netmask 255.255.255.252
gateway 192.220.24.126

#A10
auto eth1
iface eth1 inet static
address 192.220.24.0
netmask 255.255.255.192
```

Linie

```
auto lo
iface lo inet loopback

#A14
auto eth0
iface eth0 inet static
address 192.220.24.120
netmask 255.255.255.252
gateway 192.220.24.122

#A15
auto eth1
iface eth1 inet static
address 192.220.24.124
netmask 255.255.254.0

#A16
auto eth2
iface eth2 inet static
address 192.220.20.0
netmask 255.255.255.252
```

Heiter

```
auto lo
iface lo inet loopback

#A10
auto eth0
iface eth0 inet static
address 192.220.24.0
netmask 255.255.255.192
gateway 192.220.24.0

#A11
auto eth1
iface eth1 inet static
address 192.220.16.0
netmask 255.255.252.0
```

LaubHills

```
auto eth0
iface eth0 inet static
address 192.220.0.0
netmask 255.255.248.0
gateway 192.220.0.2
```

LakeKorridor

```
auto eth0
iface eth0 inet static
address 192.220.24.64
netmask 255.255.255.224
gateway 192.220.24.65
```

AppetitRegion

```
auto eth0
iface eth0 inet static
address 192.220.0.0
netmask 255.255.248.0
gateway 192.220.0.1
```

RohrRoad

```
auto eth0
iface eth0 inet static
address 192.220.8.0
netmask 255.255.252.0
gateway 192.220.8.1
```

Royal Capital

```
auto eth0
iface eth0 inet static
address 192.220.23.0
netmask 255.255.255.0
gateway 192.220.23.1
```


WilleRegion

```
auto eth0
iface eth0 inet static
address 192.220.23.0
netmask 255.255.255.0
gateway 192.220.23.2
```

SchwerMountain

```
auto eth0
iface eth0 inet static
address 192.220.24.96
netmask 255.255.255.248
gateway 192.220.24.97
```

BredtRegion

```
auto eth0
iface eth0 inet static
address 192.220.24.0
netmask 255.255.255.192
gateway 192.220.24.1
```

TurkRegion

```
auto eth0
iface eth0 inet static
address 192.220.12.0
netmask 255.255.252.0
gateway 192.220.12.1
```

GrobeForest

```
auto eth0
iface eth0 inet static
address 192.220.22.0
netmask 255.255.255.0
gateway 192.220.22.1
```

GranzChannel

```
auto eth0
iface eth0 inet static
address 192.220.20.0
netmask 255.255.254.0
gateway 192.220.20.1
```

RiegelCanyon

```
auto eth0
iface eth0 inet static
address 192.220.16.0
netmask 255.255.252.0
gateway 192.220.16.1
```

Stark

```
auto eth0
iface eth0 inet static
address 192.220.24.128
netmask 255.255.255.252
gateway 192.220.24.129
```

Richter

```
auto eth0
iface eth0 inet static
address 192.220.24.104
netmask 255.255.255.248
gateway 192.220.24.111
```

Revolte

```
auto eth0
iface eth0 inet static
address 192.220.24.104
netmask 255.255.255.248
gateway 192.220.24.105
```

Sein

```
auto eth0
iface eth0 inet static
address 192.220.16.0
netmask 255.255.252.0
gateway 192.220.16.1
```


## Routing

Denken

```
echo nameserver 192.168.122.1 > /etc/resolv.conf
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.220.24.113
```

Lugner

```
echo nameserver 192.168.122.1 > /etc/resolv.conf
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.220.24.134
```

Linie 

```
echo nameserver 192.168.122.1 > /etc/resolv.conf
route add -net 192.220.24.0 netmask 255.255.255.192 gw 192.220.24.127
route add -net 192.220.16.0 netmask 255.255.252.0 gw 192.220.24.127
```

Lawine 

```
echo nameserver 192.168.122.1 > /etc/resolv.conf
route add -net 192.220.16.0 netmask 255.255.252.0 gw 192.220.24.0
```

Heiter

```
echo nameserver 192.168.122.1 > /etc/resolv.conf
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.220.24.0
```

Himmel

```
echo nameserver 192.168.122.1 > /etc/resolv.conf
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.220.24.142
```

Flamme

```
echo nameserver 192.168.122.1 > /etc/resolv.conf
route add -net 192.220.24.96 netmask 255.255.255.248 gw 192.220.24.138
route add -net 192.220.0.0 netmask 255.255.248.0 gw 192.220.24.142
```

Fern
```
echo nameserver 192.168.122.1 > /etc/resolv.conf
route add -net 0.0.0.0 netmask 0.0.0.0 gw 192.220.24.138
```

Frieren

```
echo nameserver 192.168.122.1 > /etc/resolv.conf
route add -net 192.220.8.0 netmask 255.255.252.0 gw 192.220.24.146
route add -net 192.220.24.136 netmask 255.255.255.252 gw 192.220.24.146
route add -net 192.220.0.0 netmask 255.255.248.0 gw 192.220.24.146
route add -net 192.220.24.96 netmask 255.255.255.248 gw 192.220.24.146
route add -net 192.220.24.140 netmask 255.255.255.252 gw 192.220.24.146
```

Eisen

```
echo nameserver 192.168.122.1 > /etc/resolv.conf
route add -net 192.220.12.0 netmask 255.255.252.0 gw 192.220.24.132
route add -net 192.220.22.0 netmask 255.255.255.0 gw 192.220.24.132

route add -net 192.220.12.0 255.255.252.0 192.220.24.134
no ip 192.220.22.0 255.255.255.0 192.220.24.134

route add -net 192.220.20.0 netmask 255.255.255.0 gw 192.220.24.122
route add -net 192.220.24.124 netmask 255.255.255.252 gw 192.220.24.122
route add -net 192.220.24.0 netmask 255.255.255.192 gw 192.220.24.122
route add -net 192.220.16.0 netmask 255.255.252.0 gw 192.220.24.122
```

Aura

```
echo nameserver 192.168.122.1 > /etc/resolv.conf

#Frieren
route add -net 192.220.24.64 netmask 255.255.255.224 gw 192.220.24.150
route add -net 192.220.24.144 netmask 255.255.255.252 gw 192.220.24.150
route add -net 192.220.24.136 netmask 255.255.255.252 gw 192.220.24.150
route add -net 192.220.0.0 netmask 255.255.248.0 gw 192.220.24.150
route add -net 192.220.8.0 netmask 255.255.252.0 gw 192.220.24.150
route add -net 192.220.24.148 netmask 255.255.255.252 gw 192.220.24.150
route add -net 192.220.24.96 netmask 255.255.255.248 gw 192.220.24.150

# Denken
route add -net 192.220.23.0 netmask 255.255.255.0 gw 192.220.24.114

# Eisen
route add -net 192.220.24.128 netmask 255.255.255.252 gw 192.220.24.118
route add -net 192.220.24.132 netmask 255.255.255.252 gw 192.220.24.118
route add -net 192.220.12.0 netmask 255.255.252.0 gw 192.220.24.118
route add -net 192.220.22.0 netmask 255.255.255.0 gw 192.220.24.118
route add -net 192.220.24.120 netmask 255.255.255.252 gw 192.220.24.118
route add -net 192.220.20.0 netmask 255.255.254.0 gw 192.220.24.118
route add -net 192.220.24.124 netmask 255.255.255.252 gw 192.220.24.118
route add -net 192.220.24.0 netmask 255.255.255.192 gw 192.220.24.118
route add -net 192.220.16.0 netmask 255.255.252.0 gw 192.220.24.118
route add -net 192.220.24.104 netmask 255.255.255.248 gw 192.220.24.118
```

### Testing
![](img/testing_vlsm.png)
