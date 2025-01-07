# Pulau Pramuka Data Processing Repository

---

## Deskripsi

Repository ini berisi data hasil pengukuran pasang surut dan AWS yang dilakukan di Pulau Pramuka dan pemrosesan dari format file .excel menjadi .csv menggunakan algoritma dalam excel_to_csv.ipynb.

## Struktur Repository

### 1. csv_data/

Folder ini berisi data hasil akhir dalam format CSV, yang telah dirapikan dan diberi metadata. File-file di dalamnya adalah:

Data pasang surut (Pasut)

Data AWS (Automatic Weather Station)

### 2. raw_data/

Folder ini berisi data logsheet lapangan asli dalam format Excel, sebelum dilakukan pengolahan lebih lanjut. File-file ini merupakan hasil pencatatan langsung di lapangan.

### 3. excel_to_csv.ipynb

Notebook Jupyter ini berisi algoritma untuk mengubah data logsheet dalam folder raw_data/ menjadi file CSV di folder csv_data/. Proses ini melibatkan:

1. Memisahkan data gabungan menjadi data pasang surut dan aws.

2. Menambahkan metadata deskriptif ke dalam file CSV.

## Metadata File

Setiap file CSV di folder csv_data/ menyertakan metadata pada bagian atas file. Contoh metadata yang disertakan:

Nama file: Informasi lokasi dan jenis data.

Dibuat oleh: Nama pengolah data.

Tanggal pembuatan: Tanggal file diproses.

Deskripsi: Informasi singkat mengenai isi file (misalnya data pasang surut atau data AWS).

## Cara Penggunaan

### 1. Menyiapkan Data

Pastikan file logsheet lapangan disimpan di folder raw_data/ dengan format Excel.

### 2. Menjalankan Algoritma

Jalankan file excel_to_csv.ipynb menggunakan Jupyter Notebook atau platform serupa.

Proses ini akan menghasilkan file CSV di folder csv_data/.

### 3. Memeriksa File Hasil

Periksa folder csv_data/ untuk melihat hasil akhir. Metadata sudah otomatis ditambahkan ke setiap file.

## Teknologi yang Digunakan

Python: Untuk pengolahan data menggunakan pustaka Pandas.

Jupyter Notebook: Untuk menjalankan algoritma konversi data.

Microsoft Excel: Untuk data logsheet lapangan asli.

## Kontribusi

Jika Anda ingin berkontribusi pada pengembangan repository ini, silakan:

### 1. Fork repository ini.

### 2. Buat branch baru untuk perubahan Anda.

### 3. Ajukan pull request setelah selesai.

## Penulis

Repository ini di-<i>maintenance</i> oleh saya, Firly Hafiz Syahreza (12922004@mahasiswa.itb.ac.id).

---

Catatan: Jika Anda menemukan masalah atau memiliki saran untuk perbaikan, jangan ragu untuk membuka issue di halaman repository ini.

