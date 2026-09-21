# Ralibility & Availability
A. Availability
Jangka waktu sistem tersedia dan bisa dugunakan, konsep availability mengharuskan developer untuk membangun sistem yang harus terus berjalan meskipun terdampak suatu masalah agar pengguna dapat mengakses aplikasi setiap waktu tanpa terkendala. 

B. Ralibility
Kemampuan sistem untuk beroperasi secara konsisten dan memenuhi kebutuhan dari waktu ke waktu, termasuk menghadapi kegagalan dan melakukan recovery. 

## Single Point of Failure - SPOT
Konsep kesalahan fatal di mana terdapat titik lemah dalam arsitektur cloud yang dapat melumpuhkan seluruh layanan jika mengalami masalah. Untuk menghindarinya, Cloud Engineer merancang sistem redundan agar layanan tetap berjalan meskipun salah satu komponennya rusak.

## Redundancy (high availability) 
Praktik seorang Cloud Engineer untuk menduplikasi resources kritis sistem (seperti server, basis data, atau jaringan) di beberapa lokasi untuk memastikan layanan tetap berjalan jika terjadi kegagalan. Dengan begitu, jika satu resources mati, resources cadangan akan langsung mengambil alih secara otomatis tanpa merusak akses pengguna.

## Fault Tolerance
 kemampuan sistem untuk tetap beroperasi meskipun bagian tertentu mengalami kegagalan, bergantung pada desain dan tingkat kegagalannya. Contohnya apabila Availability Zone A di jakarta mengalami kebakaran, maka aplikasi Availability Zone B harus cepat mengambil alih trafik pengguna. 
