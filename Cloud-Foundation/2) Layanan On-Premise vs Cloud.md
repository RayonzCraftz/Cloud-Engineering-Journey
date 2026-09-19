# Jenis-jenis layanan server

## 1) On-Premise
Model infrastruktur IT di mana perangkat keras dan perangkat lunak dioperasikan secara fisik di tempat atau kantor perusahaan itu sendiri (semua resource fisik dikelola secara penuh oleh perusahaan mulai dari server yang meliputi RAM, Disk, Bandwidth, jaringan, kabel-kabel, listrik, dan lain-lain) 

Kelebihan: 
- memiliki kontrol penuh terhadap konfigurasi
- keamanan yang lebih tinggi karena data sensitif disimpan secara lokal
- Sistem dapat diakses secara normal walaupun koneksi utama perusahaan sedang gangguan

Kekurangan:
- Biaya awal sangat tinggi (butuh investasi modal besar di awal untuk membeli perangkat keras, membuat data center sendiri, sistem pendingin, dan lain-lain) 
- Biaya pemeliharaan berkelanjutan: perusahaan harus menanggung biaya listrik, perawatan alat, perbaikan hardware rusak, hingga pembaruan sistem secara mandiri) 
- Butuh tim IT khusus untuk mengelola infrastruktur yang siaga setiap hari
- Skalabilitas sangat terbatas karena jika perusahaan harus meningkatkan performa maka mereka harus membeli resources terlebih dahulu dan perlu menunggu barang sampai, apalagi mereka harus memasang dan mengelola resources tersebut secara mandiri

## 2) Public Cloud
Model infrastruktur IT di mana resource seperti server, storage, database, jaringan, dan layanan komputasi disediakan oleh cloud provider dan digunakan melalui internet. Infrastruktur fisik dimiliki dan dikelola oleh provider, sedangkan perusahaan menyewa resource sesuai kebutuhan.

Kelebihan:
- Biaya awal lebih rendah karena tidak perlu membeli hardware sendiri
- Skalabilitas tinggi, resource dapat ditambah atau dikurangi dengan cepat
- Tidak perlu mengelola hardware, listrik, pendingin, dan data center sendiri
- Banyak layanan IT dapat digunakan secara langsung

Kekurangan:
- Kontrol terhadap hardware fisik terbatas
- Biaya dapat membesar jika penggunaan resource tidak dikontrol
- Bergantung pada koneksi internet
- Risiko keamanan tetap ada jika konfigurasi cloud tidak tepat

## 3) Private Cloud
Model cloud di mana infrastruktur cloud digunakan secara eksklusif oleh satu perusahaan atau organisasi. Infrastruktur dapat berada di data center perusahaan sendiri atau dikelola oleh pihak ketiga.

Kelebihan:
- Kontrol terhadap infrastruktur dan konfigurasi lebih besar
- Keamanan dan privasi dapat disesuaikan dengan kebutuhan perusahaan
- Resource tidak digunakan bersama organisasi lain
- Cocok untuk data dan workload yang membutuhkan kontrol tinggi

Kekurangan:
- Biaya pembangunan dan pengelolaan relatif tinggi
- Membutuhkan tim IT khusus untuk mengelola infrastruktur
- Skalabilitas tidak semudah public cloud
- Perusahaan tetap bertanggung jawab terhadap banyak aspek pemeliharaan

## 4) Hybrid Cloud
Model infrastruktur yang menggabungkan private cloud atau on-premise dengan public cloud dan menghubungkan keduanya agar dapat bekerja bersama.

Kelebihan:
- Dapat menempatkan data sesuai tingkat sensitivitasnya
- Memiliki fleksibilitas dalam memilih public atau private infrastructure
- Dapat menggunakan public cloud ketika membutuhkan skalabilitas tinggi
- Dapat mengoptimalkan biaya sesuai kebutuhan workload

Kekurangan:
- Infrastruktur lebih kompleks untuk dikelola
- Membutuhkan integrasi jaringan antara private dan public cloud
- Membutuhkan tim IT dengan kemampuan yang lebih luas
- Keamanan harus dikelola pada kedua lingkungan

## 5) Multi-Cloud
Model infrastruktur di mana perusahaan menggunakan dua atau lebih cloud provider yang berbeda dalam satu lingkungan IT. Contohnya menggunakan AWS, Azure, dan Google Cloud untuk workload yang berbeda.

Kelebihan:
- Mengurangi ketergantungan pada satu cloud provider
- Dapat memilih layanan terbaik dari masing-masing provider
- Fleksibilitas lebih tinggi dalam mengelola workload
- Dapat memanfaatkan perbedaan harga dan fitur antar-provider

Kekurangan:
- Pengelolaan lebih kompleks karena setiap provider memiliki sistem berbeda
- Membutuhkan engineer yang memahami beberapa platform cloud
- Monitoring dan keamanan menjadi lebih sulit
- Integrasi antar-cloud dapat membutuhkan konfigurasi tambahan