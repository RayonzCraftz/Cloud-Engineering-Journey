## Region
Region merupakan pembagian wilayah server berdasarkan negara/kota besar utama, contohnya Singapore, Jakarta & Australia.

## Availability Zone (AZ) 
Availability Zone adalah cluster of data center atau merupakan sebuah grub yang berisikan beberapa gedung data center. Dalam 1 Region terdapat 2 atau lebih Availability Zone (AZ) dan masing masing AZ berjarak minimal 60 miles (100km) agar jika salah satu AZ terkendala maka data akan dialihkan ke AZ lain karena tidak ikut terdampak. 

## Edge Location
Server AWS yang berlokasi tersebar di banyak kota di seluruh  untuk menyimpan cache konten yang sering diakses pengguna sehingga perangkat tidak perlu mengambil data ke region utama server dan latency (delay) akan berkurang serta bandwidth server utama berkurang.AWS menyediakan solusi CDM (Content Delivery Network) bernama Amazon CloudFront yang akan menyalin cache file ke server Edge Location terdekat. 


> Catatan tambahan, 
kita bisa memanfatkan:
1. Multi Region menggunakan Route 53: jika aplikasi memerlukan backup jika data user sangat penting bagi perusahaan, maka disarankan untuk tidak menggunakan server dari 1 Region saja agar aplikasi mau senantiasa berjalan. 

2. Multi Availability Zone menggunakan Load Balancer: karena tiap AZ memiliki jarak yang jauh, jadi manfaatkan Multi AZ agar jika 1 cluster bermasalah maka server tetap berjalan. 

3. Menggunakan CloudFront: gunakan untuk mengurangi latency (delay) pengguna yang berada jauh dari Region server utama karena CloudFront menyimpan cache data yang sering diakses pengguna tersebut. 
