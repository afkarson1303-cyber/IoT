# Monitoring Network menggunakan Teknologi AR

Monitoring Network menggunakan Teknologi AR adalah salah satu interface berbasis Android yang menggunakan Teknologi Augmented Reality (AR) dan Arduino Wemos ESP32 D1 R32 yang difungsikan untuk fitur menghidupkan lampu secara otomatis pada saat Marker di scan pada kamera SmartPhone menggunakan Aplikasi APK Android yang telah terinstall di SmartPhone dan menampilkan beberapa informasi terkait dengan monitoring jaringan pada Router Mikrotik dengan informasi sebagai berikut :
1. Informasi spesifikasi mesin Router Mikrotik yang digunakan di lingkungan SMK Bakti Nusantara 666 menggunakan HTTP Request dari API disetiap mesin Router Mikrotik yang terintegrasi,
2. Informasi jumlah pengguna Internet yang terdeteksi dimasing-masing mesin Router Mikrotik yang terhubung disetiap Instansi SMK, SMP dan SD di Bakti Nusantara 666,
3. Informasi detail pengguna Internet yang terdeteksi dimasing-masing mesin Router Mikrotik menggunakan HTTP Request API dimasing-masing mesin Router tersebut.

## Demo

afkarson1303-cyber/IoT

Visualisasi Aplikasi Android menggunakan Teknologi AR :

## Unduh Berkas Pendukung

- [Download APK Android AR di sini(https://drive.google.com/file/d/16m_RKueL8MLck8QuIwHFjYhFy6xPfsFe/view?usp=sharing)

## Fitur Utama

- [x] **Augmented Reality Lamp Controller**: virtual kontrol tombol lampu yang dapat dilihat melalui AR dengan Android.
- [x] **Integrasi Wemos ESP32 D1 R32**: Mengontrol perangkat keras Relay dan Lampu Strip Led AC 220 V menggunakan Arduino Wemos D1 R32.
- [x] **Tombol On Off di Aplikasi Android**: Pengguna dapat menekan tombol On/Off untuk menghidupkan Lampu Strip Led yang terpasang pada Figura Foto.
- [x] **Otomatisasi menghidupkan Lampu Strip led dengan Scan Marker**: Sistem memberikan respon dengan menghidupkan Lampu Strip Led jika Marker terdeteksi/ di scan menggunakan Kamera pada SmartPhone yang telah terinstall Aplikasi.
- [x] **Menampilkan informasi Monitoring Jaringan di Aplikasi Android**: Sistem menampilkan informasi monitoring jaringan dengan informasi spesifikasi router mikrotik, jumlah pengguna internet dan detail pengguna internet di Aplikasi tersebut.

## Persyaratan

- Unity versi **2021.3.38f1 Personal atau yang lebih terbaru**
- **AR Vuforia** dengan release versi 10.27 untuk mengaktifkan Vuforia AR.
- **Wemos D1 R32** dan **Arduino** untuk mengontrol perangkat eksternal.
- **Build APK Android Unity** untuk membangun aplikasi ke perangkat Android/iOS.

## Instalasi

Langkah-langkah untuk mengunduh dan menjalankan proyek ini secara lokal:

1. Download APK Aplikasi Android atau Clone menggunakan Repository GitHub. 
2. Clone repository ini:

   ```bash
   git clone https://github.com/afkarson1303-cyber/IoT.git
