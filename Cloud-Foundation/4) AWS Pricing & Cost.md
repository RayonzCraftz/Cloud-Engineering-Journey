## On-Demand
sistem bayar sesuai pemakain, jika EC2 hidup salama 1 jam maka bayar 1 jam, sistem ini fleksibel tetapi mahal jika berjalan dalam waktu yang lama

## Reserved Instance
Sistem kontrak membayar server dalam jangka waktu minimal 1 atau 3 tahun, sistem ini tercakup murah (diskon up to 72%), tetapi tidak fleksibel jika bukan tipe production yang stabil. 

## Spot Instance
Kapasitas komputasi cadangan (kosong) di datacenter AWS yang dijual dengan diskon super besar (up to 90%), harga nya dapat berubah ubah secara realtime tergantung pasokan dan permintaan kapasitas pada region tersebut. 

Resiko: AWS dapat mengambil kembali server tersebut kapan saja jika buyer On-Demand membutuhkannya, pengguna Spot Instance hanya diberi notifikasi 2 menit sebelum dimatikan, sistem ini hanya cocok untuk penggunaan yang bisa dihentikan kapan saja seperti testing CI/CD, Big data dan server stateless.

```
Tools yang sangat berguna untuk menghitung estimasi harga sewa resources di Amazon Web Server adalah AWS Pricing Calculator. 
```