# Data Mahasiswa

## Deskripsi
File ini berisi data mahasiswa yang mencakup berbagai informasi terkait. File tersebut dinamakan **Data_Mahasiswa.csv** dan berisi beberapa kolom yang menyimpan data seperti identitas mahasiswa, detail akademik, dan informasi lain yang relevan.

## Struktur Data
Berikut adalah deskripsi singkat dari kolom yang ada pada file `Data_Mahasiswa.csv`:

- **Kolom 1**: Nama Mahasiswa - Menyimpan nama lengkap mahasiswa.
- **Kolom 2**: NIM - Nomor Induk Mahasiswa, sebuah identifikasi unik untuk setiap mahasiswa.
- **Kolom 3**: Jurusan - Program studi atau jurusan yang diambil mahasiswa.
- **Kolom 4**: Semester - Semester berapa mahasiswa saat ini.
- **Kolom 5**: IPK - Indeks Prestasi Kumulatif, menunjukkan performa akademik mahasiswa.

## Cara Menggunakan
Anda dapat menggunakan data ini untuk melakukan analisis akademik, membuat laporan, atau mengembangkan aplikasi yang membutuhkan informasi mahasiswa. Untuk membaca file CSV ini, Anda bisa menggunakan bahasa pemrograman seperti Python, R, atau software seperti Excel.

## Contoh Penggunaan di Python
Berikut adalah contoh kode Python untuk membaca data `Data_Mahasiswa.csv` menggunakan pandas:

```python
import pandas as pd

# Membaca file CSV
data = pd.read_csv('Data_Mahasiswa.csv')

# Menampilkan beberapa baris pertama dari data
print(data.head())
