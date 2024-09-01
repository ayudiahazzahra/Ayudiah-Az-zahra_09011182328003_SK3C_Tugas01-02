# Panduan Instalasi Linux Mint

## Daftar Isi
- [Langkah-langkah Instalasi](#langkah-langkah-instalasi)
- [Analisis Mount Point "/"](#analisis-mount-point-)
- [Penjelasan Sistem File](#penjelasan-sistem-file)

## Langkah-langkah Instalasi

### 1. Persiapan Awal
- Buat nama dan pilih ISO yang akan digunakan
  ![Langkah 1](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/1.png)

### 2. Konfigurasi Hardware
- Atur base memory dan CPU
  ![Langkah 2](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/2.png)
- Pilih hardware dengan base memory dan processors
  ![Langkah 3](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/3.png)

### 3. Penyiapan Virtual Hard Disk
- Buat virtual hard disk
  ![Langkah 4](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/4.png)

### 4. Memulai Instalasi
- Tekan start dan atur display bagian screen
  ![Langkah 5](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/5.png)
- Tampilan awal instalasi
  ![Langkah 6](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/6.png)

### 5. Pengaturan Bahasa dan Lokasi
- Pilih bahasa (contoh: US English)
  ![Langkah 7](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/7.png)
- Pilih "Erase disk and Install Linux Mint"
  ![Langkah 8](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/8.png)
- Klik "Continue"
  ![Langkah 9](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/9.png)
- Atur lokasi untuk waktu dan tanggal
  ![Langkah 10](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/10.png)

### 6. Pembuatan Akun
- Masukkan nama dan password untuk login
  ![Langkah 11](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/11.png)

### 7. Finalisasi
- Tekan "Skip" pada tampilan berikutnya
  ![Langkah 12](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/12.png)
- Masukkan password dan username yang telah dibuat
  ![Langkah 13](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/13.png)

### 8. Selesai!
- Tampilan akhir Linux Mint
  ![Langkah 14](https://github.com/ayudiahazzahra/Ayudiah-Az-zahra_09011182328003_SK3C_Tugas01-02/blob/main/14.png)

## Analisis Mount Point "/"

Tanda "/" dipilih sebagai Mount Point karena:
- "/" adalah tanda root dari partisi
- Partisi root merupakan partisi tertinggi di Linux
- Mirip dengan drive C: di Windows
- Menunjukkan pilihan "Use As Ext4" dan lainnya

## Penjelasan Sistem File

### Ext4 (4th Extended)
- Dirilis dengan kernel 2.6.28
- Mendukung pengalamatan 48-bit block
- Ukuran maksimum filesystem: 1EB (1,048,576 TB)
- Ukuran maksimum file: 16 TB
- Fitur: Fast fsck, Journal checksumming, Defragmentation support

### Ext3 (3rd Extended)
- Peningkatan dari EXT2
- Keuntungan:
  - Pemulihan cepat setelah crash sistem
  - Integritas data terjamin
  - Throughput lebih besar dari EXT2
  - Migrasi mudah dari EXT2

### FAT32 (File Allocation Table 32)
- Dikenal sejak Windows 95 SP2
- Mendukung cluster lebih besar dalam partisi
- Kompatibilitas terbatas dengan beberapa OS

### NTFS (New Technology File System)
- Diperkenalkan dengan Windows NT
- Fitur: keamanan lebih baik, kompresi file, dukungan enkripsi
- Standard untuk Windows XP ke atas

### BTRFS (B-Tree File System)
- Dikembangkan oleh Chris Mason (Oracle)
- Fitur: checksum untuk data dan metadata
- Mendukung manajemen storage yang lebih efisien
- Cocok untuk hard drive berukuran besar
