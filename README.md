# Project UAS Sistem Berbasis Mikroprosesor

## Spesifikasi Proyek

### Bagian Mikrokontroler (STM32)
1. **GPIO**  
   - Mengimplementasikan pin input dan output untuk pengendalian perangkat eksternal.
2. **Timer**  
   - Menggunakan timer bawaan STM32, baik sebagai **PWM** maupun fungsi timer lainnya.
3. **Komunikasi UART**  
   - Implementasi komunikasi serial menggunakan protokol UART untuk berinteraksi dengan ROS.

### Bagian ROS
1. **Node**  
   - Membuat minimal **2 node ROS** untuk berkomunikasi dan memproses data.
2. **Thread**  
   - Implementasi minimal **2 thread** untuk pemrosesan paralel.
3. **Serial Interface**  
   - Menggunakan komunikasi serial untuk integrasi dengan STM32.

### Catatan Penting:
- Bagian **ROS wajib menggunakan bahasa C/C++**.  
- Fitur tambahan seperti **image processing** atau **web interface** dapat menggunakan bahasa pemrograman lain.

## Penilaian
1. Rancangan Project dipresentasikan pada **Minggu Ke-15**
2. Demo Project dilakukan pada **Minggu Ke-17**
