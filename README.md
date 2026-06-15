# 📊 Dasar Pemrograman Python & Analisis Penjualan (Toko Maju Jaya)

Repositori ini berisi proyek praktikum mengenai dasar-dasar pemrograman Python hingga manipulasi data menggunakan library Pandas, NumPy, dan Matplotlib di lingkungan Jupyter Notebook. Proyek ini mensimulasikan pengolahan data transaksi penjualan pada entitas bisnis bernama "Toko Maju Jaya".

---

## 🛠️ Tech Stack & Library yang Digunakan
* **Python (Core Logic):** Implementasi variabel dasar, struktur perulangan (`for loop`), fungsi kustom (`def`), serta konsep Pemrograman Berorientasi Objek (`Class` & `Object`).
* **Pandas:** Melakukan pembacaan data eksternal berformat `.csv` dan memanipulasi struktur data DataFrame[cite: 5].
* **NumPy:** Digunakan untuk komputasi numerik array dan perhitungan statistik data penjualan[cite: 5].
* **Matplotlib:** Membuat visualisasi grafik batang (*Bar Chart*) untuk menyajikan informasi performa produk[cite: 5].

---

## 📈 Struktur Kode & Fitur Analisis

### 1. Fondasi Dasar Python (Core Python)
* **Variabel Toko:** Menyimpan dan menampilkan identitas toko (`nama_toko = "toko maju jaya"`)[cite: 5].
* **Perulangan & Akumulator:** Menggunakan logika *looping* `for i in data` untuk menjumlahkan total nilai transaksi secara manual[cite: 5].
* **Fungsi Kustom:** Membuat fungsi `rata_rata(data)` untuk menghitung nilai mean dari list data numerik[cite: 5].
* **Pemrograman Berorientasi Objek (OOP):** Mengimplementasikan struktur `class Produk` dengan metode konstruktor `__init__` untuk menginstansiasi objek produk baru secara rapi[cite: 5].

### 2. Analisis & Manipulasi Data (Pandas & NumPy)
* **Data Ingestion:** Membaca file dataset `penjualan.csv` dan menampilkan 5 baris data teratas menggunakan fungsi `.head()`[cite: 5].
* **Agregasi Data:** Menghitung total keseluruhan volume penjualan dari kolom `Penjualan` dengan fungsi `.sum()`[cite: 5].
* **Kalkulasi Statistik:** Menggunakan fungsi bawaan NumPy untuk mencari nilai rata-rata (`np.mean`), angka penjualan tertinggi (`np.max`), dan penjualan terendah (`np.min`) dari data transaksi[cite: 5].

### 3. Visualisasi Data (Data Visualization)
* **Data Grouping:** Mengelompokkan total kuantitas penjualan berdasarkan nama masing-masing produk (`data.groupby("Produk")["Penjualan"].sum()`)[cite: 5].
* **Bar Chart Generation:** Memproyeksikan indeks produk ke sumbu X dan nilai total penjualan ke sumbu Y ke dalam grafik batang, serta melengkapinya dengan label judul, label X, dan label Y yang informatif[cite: 5].

---

## 📊 Hasil Analisis & Kesimpulan
* Berdasarkan grafik penjualan yang dieksekusi, produk **Mouse** mencatatkan volume penjualan tertinggi (mencapai 70 total kuantitas), diikuti oleh Keyboard dan Laptop[cite: 5].
* Proyek ini berhasil menunjukkan kemampuan dasar dalam mengintegrasikan logika pemrograman Python murni dengan *tools* analisis data modern untuk kebutuhan penarikan kesimpulan bisnis (*Business Insights*)[cite: 5].

---
*Proyek ini diselesaikan sebagai bagian dari portofolio praktikum Pengantar Big Data.*
