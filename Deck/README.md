# Kimia Farma Business Performance Analytics (2020–2023)

## 📌 Project Overview
Sebagai perusahaan dengan jaringan operasional yang tersebar di seluruh Indonesia, Kimia Farma menghasilkan data transaksi dan operasional dalam jumlah besar setiap tahunnya. Data tersebut mencakup informasi terkait penjualan, produk, cabang, serta penilaian pelanggan. Namun, tanpa analisis data yang tepat, data yang tersedia belum dapat dimanfaatkan secara optimal untuk mengevaluasi kinerja bisnis secara menyeluruh. Oleh karena itu, proyek ini berfokus pada analisis kinerja bisnis Kimia Farma pada periode 2020–2023 untuk mengidentifikasi tren pendapatan dan profitabilitas, memahami pola transaksi pelanggan, serta mengevaluasi performa cabang dan wilayah.

Hasil analisis ini diharapkan dapat menjadi dasar dalam pengambilan keputusan strategis berbasis data guna meningkatkan kinerja bisnis Kimia Farma.

---

## 📂 Data yang Digunakan
Proyek ini menggunakan empat dataset utama, yaitu:

1. **kf_final_transaction**  
   Data transaksi penjualan yang mencakup tanggal transaksi, produk, cabang, harga, diskon, serta rating transaksi.
2. **kf_product**  
   Data persediaan produk di setiap cabang Kimia Farma.

3. **kf_inventory**  
   Data cabang Kimia Farma yang berisi informasi nama cabang, lokasi, dan rating cabang.

4. **kf_kantor_cabang**  
   Data master produk yang mencakup nama produk, kategori produk, dan harga dasar.

Keempat dataset tersebut diintegrasikan di Google BigQuery dan digabungkan ke dalam satu tabel analisis yang digunakan sebagai dasar untuk analisis data serta pembuatan dashboard kinerja bisnis Kimia Farma.

---

## 🎯 Tujuan Analisis
Tujuan dari analisis ini adalah untuk:
1. Menganalisis kinerja pendapatan dan profit Kimia Farma selama periode 2020–2023.
2. Mengidentifikasi provinsi dengan jumlah transaksi dan nett sales tertinggi.
3. Mengevaluasi perbandingan antara rating cabang dan rating transaksi pelanggan.
4. Menganalisis distribusi profit Kimia Farma di setiap provinsi di Indonesia.

---

## ⚙️ Proses Pengolahan Data
1. Import Dataset ke BigQuery

   Proses analisis diawali dengan pembuatan project pada Google Cloud Platform dengan nama: **Rakamin Academy Data Analytics**
   Kemudian dibuat dataset dengan nama: **kimia_farma**
   Langkah-langkah yang dilakukan:
   1. Membuat dataset Kimia Farma di BigQuery
   2. Mengimpor seluruh dataset ke dalam BigQuery
   3. Menyiapkan data agar siap digunakan untuk analisis
3. Pembuatan Tabel Analisis

   Setelah seluruh dataset diintegrasikan di Google BigQuery, dibuat sebuah tabel analisis yang berfungsi sebagai sumber data utama untuk proses visualisasi dan analisis kinerja bisnis Kimia Farma.
   
   Tabel ini menggabungkan data transaksi, produk, cabang, dan wilayah ke dalam satu tabel sehingga memudahkan analisis terkait pendapatan, profitabilitas, serta penilaian pelanggan pada periode 2020–2023.

4. Query SQL (BigQuery)

   Tabel analisis dibuat menggunakan query SQL di Google BigQuery dengan menggabungkan empat dataset utama Kimia Farma.
   
   Query ini menghasilkan satu tabel terintegrasi yang siap digunakan untuk analisis data dan visualisasi dashboard.

---
## 📊 Dashboard Kinerja Bisnis
Dashboard ini menampilkan visualisasi interaktif mengenai kinerja bisnis Kimia Farma yang meliputi:
- Tren penjualan dan profit
- Distribusi transaksi berdasarkan wilayah
- Performa cabang
- Analisis rating pelanggan 

🔗 Link Dashboard Interaktif: https://lookerstudio.google.com/reporting/94c81f1f-d1d9-470b-87a1-dc9488a32611

---
## 📈 Insight Data
1. Kinerja Finansial Secara Keseluruhan

   Berdasarkan hasil analisis dashboard selama periode 2020–2023, Kimia Farma mencatat:
   - Total Transaksi: 672.458 transaksi
   - Total Nett Sales: 321,2 miliar
   - Total Nett Profit: 91,2 miliar
   - Rata-rata Rating Transaksi: 4,0
   
   Hal ini menunjukkan bahwa Kimia Farma memiliki volume transaksi yang tinggi dengan tingkat kepuasan pelanggan yang cukup baik.
2. Tren Performa Finansial

   Analisis tren pendapatan tahunan menunjukkan bahwa:
   - Nett sales tahunan berada pada kisaran 80–81 miliar per tahun
   - Terjadi penurunan ringan pada tahun 2021
   - Penjualan kembali meningkat pada tahun 2022
   - Tahun 2023 relatif stabil
   
   Tren penjualan bulanan menunjukkan bahwa:
   - Penjualan berada pada kisaran 25–28 miliar per bulan
   - Pola penjualan relatif konsisten sepanjang tahun
   
   Hal ini menunjukkan bahwa pendapatan Kimia Farma cukup stabil meskipun terdapat dinamika pasar.
3. Performa Wilayah dan Kontribusi Provinsi

   Berdasarkan jumlah transaksi dan nilai penjualan per provinsi:
   - Jawa Barat menjadi provinsi dengan jumlah transaksi dan nett sales tertinggi
   - Provinsi lain seperti Sumatra Utara, Jawa Tengah, dan Jawa Timur juga memberikan kontribusi signifikan
   
   Namun terdapat beberapa provinsi dengan volume transaksi tinggi tetapi nilai penjualan relatif lebih rendah, sehingga diperlukan strategi optimalisasi harga dan produk di wilayah tersebut.
5. Kualitas Layanan dan Kepuasan Pelanggan

   Analisis perbandingan antara rating cabang dan rating transaksi menunjukkan bahwa beberapa provinsi seperti:
   - Kalimantan Utara
   - Kalimantan Tengah
   - Bangka Belitung
   
   memiliki:
   - Rating cabang tinggi (4,6–4,7)
   - Namun rating transaksi lebih rendah (sekitar 3,9)
   
   Hal ini menunjukkan bahwa meskipun fasilitas atau layanan cabang dinilai baik, masih terdapat potensi perbaikan dalam pengalaman transaksi pelanggan.
7. Distribusi Profit Secara Geografis

   Berdasarkan peta distribusi profit:
   - Provinsi di Pulau Jawa memberikan kontribusi profit terbesar
   - Wilayah luar Jawa memiliki kontribusi profit yang lebih rendah
   
   Hal ini menunjukkan adanya peluang ekspansi dan optimalisasi bisnis di wilayah luar Jawa untuk meningkatkan pertumbuhan jangka panjang.

---

## 💡 Kesimpulan dan Rekomendasi

**Kesimpulan**
- Kinerja bisnis Kimia Farma relatif stabil dan konsisten
- Tren pendapatan menunjukkan fluktuasi yang terkendali
- Kontribusi pendapatan dan profit masih terpusat di Pulau Jawa
- Terdapat kesenjangan antara kualitas cabang dan pengalaman transaksi pelanggan

**Rekomendasi**
- Optimalisasi strategi bisnis di wilayah luar Jawa
- Peningkatan pengalaman transaksi pelanggan
- Implementasi strategi berbasis data untuk cabang dan wilayah
- Monitoring kinerja bisnis secara berkala melalui dashboard analitik
---

## 🛠 Tools & Technologies
- **Google BigQuery** – Data storage, data processing, and SQL-based analysis  
- **Google Looker Studio** – Data visualization and interactive dashboard creation  
- **Visual Studio Code** – SQL script documentation  
- **GitHub** – Version control and project repository  
---
## 👩‍💻 Author
Project by: Khamidah Arsyad Daud 

Machine Learning & Data Analysis Enthusiast


