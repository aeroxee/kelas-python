# Pengenalan Python dan Variabel

## Apa itu Python?

- Python adalah bahasa pemrograman tingkat tinggi yang mudah dipelajari.
- Python diciptakan oleh Guido Van Rossum pada akhir 1980-an.
- Python dirancang dengan fokus pada keterbacaan kode dan produktifitas pengembangan.

### Ciri-ciri utama python:

1. Mudah Dipelajari dan Dibaca:
    - Python menggunakan sintaks yang jelas dan ekspresif, membuatnya mudah dipelajari dan dibaca oleh programmer baru maupun yang berpengalaman.

2. Interpretatif:
    - Python adalah bahasa interpretatif, yang berarti kode Anda dieksekusi baris per baris oleh interpreter tanpa perlu dikompilasi terlebih dahulu.

3. Dinamis dan Tipe Data Dinamis:
    - Python adalah bahasa pemrograman dinamis, yang berarti Anda tidak perlu mendeklarasikan tipe variabel secara eksplisit. Interpreter Python menangani tipe data secara otomatis.

4. Multiparadigma:
    - Python mendukung paradigma pemrograman seperti pemrograman berorientasi objek (OOP), pemrograman prosedural, dan pemrograman fungsional.

5. Ekosistem dan Komunitas yang Kuat:
    - Python memiliki ekosistem yang kaya dengan berbagai pustaka dan modul yang mendukung berbagai aplikasi, mulai dari pengembangan web hingga kecerdasan buatan.

6. Portabel:
    - Kode Python dapat dijalankan di berbagai platform dan sistem operasi, termasuk Windows, macOS, dan Linux.

7. Pemeliharaan Kode yang Mudah:
    - Dengan fokus pada keterbacaan dan kesederhanaan, Python mendorong gaya penulisan kode yang bersih dan mudah dipelihara.

### Kegunaan Python

Python memiliki berbagai kegunaan dan telah menjadi salah satu bahasa pemrograman yang paling populer dan serbaguna. Berikut adalah beberapa kegunaan utama Python:

1. Pengembangan Web:
    - Python digunakan dalam berbagai kerangka kerja web seperti Django dan Flask untuk membangun aplikasi web yang efisien dan skalabel.

2. Ilmu Data dan Analisis:
    - Python menjadi bahasa pemrograman utama dalam ilmu data dan analisis data. Pustaka seperti NumPy, Pandas, dan Matplotlib membantu dalam manipulasi data, analisis statistik, dan visualisasi.

3. Kecerdasan Buatan (AI) dan Pembelajaran Mesin (ML):
    - Python sangat populer dalam pengembangan proyek kecerdasan buatan dan machine learning. Framework seperti TensorFlow dan PyTorch banyak digunakan untuk mengembangkan model ML dan DL.

4. Automasi dan Skriping:
    - Python sering digunakan untuk menulis skrip dan otomasi tugas-tugas sistem atau tugas-tugas yang berulang. Hal ini membuatnya menjadi pilihan yang baik untuk administrasi sistem dan otomasi tugas-tugas sehari-hari.

5. Pengembangan Perangkat Lunak Umum:
    - Python dapat digunakan untuk mengembangkan berbagai jenis perangkat lunak, mulai dari aplikasi desktop hingga perangkat lunak server.

6. Pengembangan Game:
    - Dengan bantuan pustaka seperti Pygame, Python dapat digunakan untuk mengembangkan permainan sederhana hingga permainan yang lebih kompleks.

7. Pengembangan Aplikasi Mobile:
    - Meskipun bukan pilihan utama untuk pengembangan aplikasi mobile, Python dapat digunakan dengan kerangka kerja seperti Kivy atau BeeWare untuk membangun aplikasi mobile lintas platform.

8. Pengembangan Situs Web dan API:
    - Python dapat digunakan untuk mengembangkan situs web dan API dengan bantuan kerangka kerja seperti Flask atau FastAPI.

9. Pengujian Perangkat Lunak:
    - Python digunakan secara luas dalam pengujian perangkat lunak dengan memanfaatkan kerangka kerja seperti Pytest.

10. Pengembangan IoT (Internet of Things):
    - Python digunakan dalam pengembangan perangkat IoT untuk mengendalikan dan mengumpulkan data dari perangkat keras.

### Instalasi Python

**Windows**:

1. Unduh Instalator:
    - Kunjungi situs web resmi Python di python.org.
    - Klik pada tombol "Downloads" di bagian atas halaman.
    - Pilih versi Python terbaru yang sesuai dengan sistem operasi Anda (misalnya, Python 3.9.x).

2. Mulai Instalasi:
    - Buka berkas instalator yang telah diunduh.
    - Pilih opsi "Add Python 3.x to PATH" selama proses instalasi.
    - Klik "Install Now" dan tunggu proses instalasi selesai.

3. Verifikasi Instalasi:
    - Buka Command Prompt atau PowerShell.
    - Ketik `python --version atau python -V` untuk memastikan Python telah terinstal dengan benar.

**macOS**:

1. Instalasi Homebrew (Opsional):
    - Jika Anda menggunakan Homebrew, Anda dapat menginstal Python dengan perintah: brew install python.

2. Unduh Instalator:
    - Kunjungi situs web resmi Python di python.org.
    - Klik pada tombol "Downloads" di bagian atas halaman.
    - Pilih versi Python terbaru yang sesuai dengan sistem operasi Anda (misalnya, Python 3.9.x).

3. Mulai Instalasi:
    - Buka berkas instalator yang telah diunduh.
    - Ikuti petunjuk pada layar untuk menyelesaikan instalasi.

4. Verifikasi Instalasi:
    - Buka Terminal.
    - Ketik `python3 --version atau python3 -V` untuk memastikan Python telah terinstal dengan benar.

**Linux**:

1. Menggunakan Package Manager:
    - Banyak distribusi Linux sudah menyertakan Python. Gunakan package manager distribusi Anda untuk menginstal Python. Contoh untuk Ubuntu: `sudo apt-get install python3`.

2. Menggunakan Instalator Resmi:
    - Kunjungi situs web resmi Python di python.org.
    - Klik pada tombol "Downloads" di bagian atas halaman.
    - Pilih versi Python terbaru yang sesuai dengan sistem operasi Anda (misalnya, Python 3.9.x).
    - Ikuti petunjuk pada halaman tersebut untuk menginstal Python.

3. Verifikasi Instalasi:
    - Buka Terminal.
    - Ketik `python3 --version atau python3 -V` untuk memastikan Python telah terinstal dengan benar.

---

## Membuat Lingkungan Kerja

Lingkungan kerja pengembangan (development environment) sangat penting dalam pengembangan perangkat lunak. Lingkungan kerja menyediakan alat dan sumber daya yang diperlukan untuk menulis, menguji, dan menjalankan kode. Berikut adalah beberapa kegunaan utama dari lingkungan kerja pengembangan:

1. Pengelolaan Proyek:
    - Lingkungan kerja menyediakan struktur untuk mengelola proyek perangkat lunak. Ini mencakup organisasi struktur direktori, manajemen dependensi, dan pengelolaan versi menggunakan sistem kontrol versi seperti Git.
2. Pengkodean yang Efisien:
    - Lingkungan kerja biasanya dilengkapi dengan editor kode yang kuat dan fitur otomatisasi, seperti penyorotan sintaks, penyelesaian kode, dan saran refaktor. Ini membantu pengembang menulis kode dengan lebih efisien.
3. Manajemen Dependensi:
    - Lingkungan kerja memungkinkan pengelolaan dependensi proyek dengan menggunakan manajer paket seperti pip untuk Python atau npm untuk JavaScript. Ini membantu mengelola versi dan instalasi pustaka atau modul pihak ketiga.
4. Debugging dan Profiling:
    - Lingkungan kerja menyediakan alat untuk debugging kode, memantau kinerja, dan melakukan profil terhadap aplikasi. Ini membantu pengembang mengidentifikasi dan mengatasi masalah dalam kode mereka.
5. Uji dan Otomasi:
    - Lingkungan kerja mendukung otomatisasi pengujian dengan menyediakan kerangka pengujian dan alat pengujian unit. Ini mempermudah pengembang untuk menguji fungsionalitas kode mereka secara otomatis.
6. Dokumentasi:
    - Lingkungan kerja dapat mendukung pembuatan dokumentasi dengan menyediakan alat untuk menghasilkan dokumentasi otomatis dari kode sumber. Ini membantu dalam memelihara dokumentasi proyek dengan lebih efisien.
7. Integrasi dengan Alat Eksternal:
    - Lingkungan kerja dapat terintegrasi dengan berbagai alat eksternal seperti sistem manajemen basis data, layanan pihak ketiga, atau alat kolaborasi tim. Ini memfasilitasi kerja kolaboratif dan integrasi dengan infrastruktur proyek.
8. Pengembangan Berbasis Cloud:
    - Beberapa lingkungan kerja menyediakan dukungan untuk pengembangan berbasis cloud, memungkinkan tim untuk bekerja secara terdistribusi dan menyimpan proyek mereka secara aman di cloud.
9. Optimasi Kinerja:
    - Lingkungan kerja dapat membantu dalam mengoptimalkan kinerja aplikasi dengan menyediakan alat analisis dan pemantauan kinerja.
10. Keamanan:
    - Lingkungan kerja dapat menyertakan alat untuk memeriksa keamanan kode, mengidentifikasi potensi kerentanan, dan memastikan kepatuhan terhadap praktik keamanan.
11. Konfigurasi dan Pengaturan:
    - Lingkungan kerja memungkinkan pengelolaan konfigurasi proyek, termasuk pengaturan lingkungan dan variabel konfigurasi proyek.

### Cara membuat lingkungan (environtment)

1. Buka terminal / cmd pada komputer anda.
2. Buat folder dan masuk kedalam folder
```bash title="For Linux/Unix"
mkdir Projects
cd Projects
mkdir Python
cd Python
```
3. Lalu install Virtualenv dengan menggunakan PIP.
```
pip install virtualenv
```
4. Kemudian buat environtmennya
```
# python -m venv nama-environtment

# Example
python -m venv kelaspython
```
5. Lalu aktifkan environtment dengan cara
```title="Linux"
source kelaspython/bin/activate
```
```title="Windows"
.\kelaspython\Scripts\bin\activate.bat
```

## Program Hello World

1. Buat file didalam folder yang telah kita buat [sebelumnya](#cara-membuat-lingkungan-environtment).
2. Buat file dengan nama `helloworld.py`.
3. Lalu isi dengan kode berikut:
```py
print("Hello World")
```
4. Lalu jalankan perintah di CMD: `python helloworld.py`. Dan output berupa:
```
Hello World
```

---

## Variable

Dalam pemrograman, variabel adalah suatu lokasi penyimpanan yang diberi nama dan digunakan untuk menyimpan nilai atau informasi. Variabel memungkinkan programmer untuk menetapkan nama kepada suatu nilai atau data, sehingga nantinya nilai tersebut dapat diakses dan dimanipulasi dalam program.

```py
# Mendefinisikan variabel dengan nama `umur` dan memberikan nilai 25
umur = 19

# Menggunakan variabel dalam operasi matematika
tahun_lahir = 2024 - umur
print("Tahun lahir:", tahun_lahir)
```

### Python bersifat dinamis

Python adalah bahasa pemrograman yang bersifat dinamis. artinya kita tidak perlu mendeklarasikan tipe data untuk variabel. Tipe data variable ditentukan secara otomatis saat nilai diberikan. Berikut perbedaan bahasa python yang bersifat dinamis dengan bahasa C yang bersifat statis.

```py title="Bahasa Python"
angka = 40      # variabel angka memiliki tipe data integer secara otomatis.
teks = "Hello"  # variabel teks memiliki tipe data string secara otomatis.
```

```c title="Bahasa C"
int angka = 40;         // variabel angka memiliki tipe data integer
char teks[5] = "Hello"  // variabel angka memiliki tipe data char.
```