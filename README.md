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
Penamaan subnet yang kami gunakan untuk metode CIDR adalah sebagai berikut:  

![topologi-cidr](https://github.com/NizamHakim/Jarkom-Modul-4-E28-2023/assets/91371703/14a72d6e-9090-4e77-b173-ec635a82941b)

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
### Subnet Tree
### Testing