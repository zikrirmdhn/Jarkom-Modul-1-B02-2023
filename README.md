# Jarkom-Modul-1-B02-2023

### Kelompok B02 dengan anggota:
| **No** | **Nama** | **NRP** | 
| ------------- | ------------- | --------- |
| 1 | Abdurrahman Farimza  | 5025201125 | 
| 2 | Muhammad Zikri Ramadhan | 5025211085 |
| 3 | Adrian Aziz Santoso | 5025221229 |

## Soal 1

## Soal 2

Untuk mendapatkan web server yang digunakan, kita gunakan filtar HTTP lalu cukup follow http untuk mendapatkan data yang dibutuhkan
    

## Soal 3

Filter dengan (ip.src == 239.255.255.250 && udp.port == 3702) || (ip.dst == 239.255.255.250 && udp.port == 3702) untuk melihat banyak paket yang tercapture dan protokolnya


## Soal 4

Filter dengan frame.number == 130, dapat dilihat checksumnya 0x18e5


## Soal 5

## Soal 6

## Soal 7

Untuk mendapatkan jumlah packet yang menuju IP 184.87.193.88, filter menggunakan ip.dst == 184.87.193.88
    

## Soal 8

Filter untuk mendapatkan semua protokol paket yang menuju port 80 adalah tcp.dstport == 80 || udp.dstport == 80


## Soal 9

Untuk mendapatkan paket yang berasal dari alamat 10.51.40.1 tetapi tidak menuju ke alamat 10.39.55.34, gunakan filter ip.src == 10.51.40.1 && ip.dst != 10.39.55.34


## Soal 10

