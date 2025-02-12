# LAPORAN-TRANSFER-FILE-DARI-PC-KE-PC-MENGGUNAKAN-LAN
| Nama        | ADIN ADEGUNA |
|--------------|------------|
| NIM        | 09030282327031 |
| Program Studi | Teknik Komputer |




Mengirim file menggunakan kabel UTP (Unshielded Twisted Pair) antar dua komputer

Persiapan
Peralatan yang dibutuhkan

1. 2 komputer atau laptop dengan port Ethernet (RJ-45)

![Gambar WhatsApp 2025-02-12 pukul 19 45 26_a12cc091](https://github.com/user-attachments/assets/a0b93595-a0dd-4b42-980d-05fd94d783c8)

2. Gunakan kabel UTP jenis crossover untuk langsung menghubungkan dua perangkat tanpa switch

![Gambar WhatsApp 2025-02-12 pukul 19 38 20_679bc5a6](https://github.com/user-attachments/assets/d7151419-d310-4ef5-b702-0b6525bd3391)

Hubungkan kabel UTP ke port Ethernet masing-masing perangkat
3. Lalu atur IP Address secara manual
Buka Control Panel > Network and Sharing Center
Pilih Change adapter se

![Image](https://github.com/user-attachments/assets/61f0e99c-595e-4b06-9b02-30138639feb7)



Klik kanan pada Ethernet > Properties

![Image](https://github.com/user-attachments/assets/9783cc6b-0c05-45d9-a48c-8ce93f6a6cd8)

Pilih Internet Protocol Version 4 (TCP/IPv4) > Properties
Atur IP Address:

![Image](https://github.com/user-attachments/assets/9afecc61-5dd0-488f-845d-40391db4a20e)

Komputer 1:
IP Address: 192.168.0.15
Subnet Mask: 255.255.255.0
Komputer 2:
IP Address: 192.168.0.10
Subnet Mask: 255.255.255.0
Klik OK lalu Close
Pastikan Koneksi Berjalan dengan Baik

4. Kemudian buka Command Prompt (cmd)
   Ketik perintah:
   ipconfig dari komputer pertama

![Image](https://github.com/user-attachments/assets/1d9e8f78-9a96-43b4-9f59-6bcffbe18d76)

dan ketik perintah
ping 192.168.1.3
dari komputer kedua
Jika ada balasan (Reply from ...) berarti koneksi sudah berhasil

Next, untuk Mengirim File Menggunakan Folder Sharing (Windows)
Aktifkan File Sharing:

Buka Control Panel > Network and Sharing Center
Pilih Change advanced sharing settings

![Image](https://github.com/user-attachments/assets/57dff676-a009-4f1c-aad7-cc021b4c552e)

Aktifkan Turn on file and printer sharing
Nonaktifkan password-protected sharing jika ingin akses tanpa login

Kemudian untuk bagikan Folder:
Klik kanan folder yang ingin dikirim → Properties

![Image](https://github.com/user-attachments/assets/2a8689e3-333e-4352-a290-d5d9eab04557)

Masuk ke tab Sharing → Klik Advanced Sharing

![Image](https://github.com/user-attachments/assets/d1edea27-7dee-4cc9-8347-7a6742a7cc7a)

Centang Share this folder dan atur permission

![Image](https://github.com/user-attachments/assets/eaf5e328-4195-440e-b353-9510c35fd5db)

Next, atur permission, dan kemudian Klik Apply dan OK

![Image](https://github.com/user-attachments/assets/de34d0d8-58af-4f8e-b054-0f3b85d4b0bb)

Setelah berhasil melakukan sharing file

![Image](https://github.com/user-attachments/assets/f02e9104-ae2f-4b3b-9541-8d28f33befb3)

lakukan pengecekan pada komputer ke 2 dengan cara
Buka File Explorer → ketik \192.168.1.3 di address bar

![Image](https://github.com/user-attachments/assets/18bbe017-9ef5-4820-b2cc-6919ebea54fb)

Pilih folder yang dibagikan dan salin file.

![Image](https://github.com/user-attachments/assets/7c2ec9af-9469-4671-8593-1e04b0658ecf)

dan SELESAI!!!

Terimakasihh...
preview
