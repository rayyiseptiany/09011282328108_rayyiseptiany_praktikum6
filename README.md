# 09011282328108_rayyiseptiany_praktikum6

## 1. sudo apt update && sudo apt upgrade memperbarui daftar paket dan mengupgrade semua paket terinstal ke versi terbaru.
![s1](https://github.com/user-attachments/assets/f1618a73-9922-468b-890d-75ea027fe010)
## 2. Sudo apt install openssh-server. Perintah ini digunakan untuk menginstal server OpenSSH pada sistem Anda, sehingga Anda dapat mengaksesnya melalui protokol SSH secara aman.
![s2](https://github.com/user-attachments/assets/11b78ebd-b99c-4dd4-b37a-d6dab093f258)
## 3. sudo systemctl enable --now ssh digunakan untuk mengaktifkan layanan SSH agar dimulai otomatis saat sistem boot dan juga langsung memulai layanan SSH saat ini. Dengan ini, Anda dapat segera mengakses server menggunakan SSH.
![s3](https://github.com/user-attachments/assets/32079065-bb86-4fd4-86af-29f1590dd3ca)
## 4. sudo systemctl status ssh digunakan untuk memeriksa status layanan SSH, menunjukkan apakah layanan aktif, tidak aktif, atau mengalami kesalahan, beserta informasi terkait lainnya
![s4](https://github.com/user-attachments/assets/7b38d8cc-fa9c-4abd-9ef9-9fbc50d1d5c5)
## 5. sudo ufw status digunakan untuk memeriksa status Firewall UFW (Uncomplicated Firewall). Perintah ini menunjukkan apakah firewall aktif atau tidak, serta aturan yang diterapkan.
![s5](https://github.com/user-attachments/assets/0241f6f3-e292-45f4-9e85-edc0b633a876)
## 6. sudo ufw allow ssh digunakan untuk mengizinkan lalu lintas SSH melalui firewall UFW (Uncomplicated Firewall).
![s6](https://github.com/user-attachments/assets/bbf484ce-1565-4010-a04c-c361b53f8c0e)
## 7. ssh meita@10.8.140.171 digunakan untuk menghubungkan ke server jarak jauh secara aman melalui protokol SSH, menggunakan nama pengguna dan alamat IP yang ditentukan.
![s8](https://github.com/user-attachments/assets/c4385a7e-7191-481a-9da1-b871e6b0b9c8)
![s7](https://github.com/user-attachments/assets/02b094d6-b25a-4e17-9710-f59851a5f628)
## 8. sudo cp /etc/ssh/sshd_config /etc/ssh/sshd_config.initial digunakan untuk membuat salinan cadangan file konfigurasi SSH dengan nama sshd_config.initial.
![s88](https://github.com/user-attachments/assets/4c775881-874e-41f5-be80-50ff23145e58)
## 9. sudo nano /etc/ssh/sshd_config digunakan untuk membuka dan mengedit file konfigurasi SSH dengan editor teks Nano menggunakan hak akses administrator. 
## Perintah `ssh -p 49532 meita@10.8.140.171` digunakan untuk menghubungkan ke server SSH melalui port khusus yang ditentukan.
![s12](https://github.com/user-attachments/assets/610277f5-d150-44fd-9c54-9468ba08243e)
## 10. Untuk meningkatkan keamanan SSH, ikuti langkah-langkah ini: 
### 1. **Ubah Port SSH**: Gunakan port dari rentang dinamis (49152 - 65535), misalnya ubah port menjadi `49532` dengan membuka file konfigurasi SSH (`/etc/ssh/sshd_config`), menghapus tanda komentar pada baris port, dan menggantinya dengan nilai baru.
![s9](https://github.com/user-attachments/assets/c10057b5-c2d9-403e-af43-33cd81cd79e3)
### 2. **Larangan Login Superuser**: Blokir login sebagai superuser dengan mengubah konfigurasi `PermitRootLogin` menjadi "No". Ini membantu meningkatkan keamanan server SSH secara signifikan. 
![s10](https://github.com/user-attachments/assets/aea3a744-f9f8-45d7-ab02-476105669bd6)
### 3. **Aktifkan Autentikasi Kunci**: Ubah metode autentikasi menjadi menggunakan kunci (key-based authentication) dengan memastikan opsi `PasswordAuthentication` diatur ke "Yes". 
![s11](https://github.com/user-attachments/assets/d80c6488-f8cb-4aaa-bcc7-05034644966a)

# Menginstal Putty

1. Update Repository
   
![p1](https://github.com/user-attachments/assets/aa85581e-9bb2-4a57-bb7c-997e29071ba0)

2. Install Putty
   
![p2](https://github.com/user-attachments/assets/c9490f3b-770e-4b48-9370-ecef160ff782)

3. Menampilkan versi Putty
   
![p3](https://github.com/user-attachments/assets/61d2c201-c1ff-4180-9966-6607a4f9ccda)

4. Tamipaln saat putty dibuka
   
![p4](https://github.com/user-attachments/assets/7c1ea441-6a5f-4aa7-9d6d-40ebe76cd988)


