📊 Customer Segmentation RFM Analysis – Automobile Sales Data

By Ardy Ansyah

Analisis ini merupakan proyek utama dalam portfolio Data Analyst, yang berfokus pada segmentasi pelanggan menggunakan metode RFM (Recency, Frequency, Monetary) untuk mendukung strategi pemasaran, retensi pelanggan, dan peningkatan pendapatan perusahaan.

Dataset yang digunakan adalah Automobile Sales Data dengan 2.747 entri dan 20 kolom, berisi informasi tentang transaksi penjualan, pelanggan, dan produk.

📘 Ringkasan Proyek

Judul: Segmentasi Pelanggan pada Automobile Sales Data menggunakan Analisis RFM.

Tujuan:
Mengelompokkan pelanggan berdasarkan Recency, Frequency, dan Monetary untuk memahami:
- perilaku pembelian
- loyalitas pelanggan
- potensi churn
- serta peluang peningkatan pendapatan.

Output utama:
- Segmentasi pelanggan
- Dashboard interaktif (Power BI)
- Insight dan rekomendasi strategis

🏛️ Business Problem

Perusahaan perlu memahami:
- Pelanggan mana yang paling menguntungkan?
- Siapa yang berpotensi churn?
- Bagaimana tren penjualan dari tahun ke tahun?
- Produk apa yang paling menghasilkan pendapatan?
- Negara mana dengan pelanggan terbanyak?
- Bagaimana hubungan antara jumlah order dan pendapatan?
- Bagaimana karakteristik pelanggan berdasarkan skala order?

Hasil akhir digunakan untuk mendukung keputusan pemasaran, strategi retensi, dan peningkatan profitabilitas.

📂 Pemahaman Data
- Dataset diperoleh dari Kaggle
- 2.747 baris, 20 kolom
- Tidak ada duplikasi
- Tidak ada missing value
- Outlier masih dalam batas wajar
- Kolom days_since_lastorder dihapus karena tidak relevan
- Tipe data: float, int, datetime, object

🔎 Proses Analisis
- Data Cleaning & Preprocessing
- Feature Engineering (R, F, M scoring)
- Segmentasi Pelanggan (Priority, Loyal, At Risk, Lost, dll.)
- Visualisasi Data menggunakan Python & Power BI
- Analisis Insight
- Penyusunan Rekomendasi Bisnis

📥 Insight Bisnis

1️⃣ Produk Penyumbang Pendapatan Tertinggi
- Classic Cars mendominasi pendapatan pada hampir seluruh segmen, terutama Priority, At Risk, dan Potential Loyalists.
- Perusahaan harus menjaga kualitas & stok produk ini.

2️⃣ Perilaku Pelanggan Berdasarkan Skala Order
- Mayoritas pelanggan membeli dalam skala kecil dan menengah.
- Order besar (Large) masih sangat kecil di semua segmen.

3️⃣ Dominasi Segmen Pelanggan
- At Risk menjadi segmen terbesar (34.83%).
- Perlu strategi retensi untuk mencegah churn.

4️⃣ Negara dengan Pelanggan Terbanyak
- USA merupakan pasar terbesar.
- Perlu kampanye dan distribusi produk yang lebih fokus untuk wilayah ini.

5️⃣ Pelanggan Low RFM Score tapi High Monetary
- Banyak berasal dari segmen At Risk dan Lost, sebagian besar dari USA.
- Perlu program flash sale, diskon eksklusif, dan reminder.

6️⃣ Tren Penjualan Berdasarkan Tahun
- At Risk mengalami penurunan tajam dari 2019 ke 2020 → urgensi strategi retensi.
- Priority meningkat hingga 2019, lalu sedikit menurun.
- Segmen Loyal dan Potential Loyalists stabil tetapi perlu diperkuat.

7️⃣ Hubungan Order Volume dengan Pendapatan
- Segmen Priority memberikan pendapatan tertinggi (hingga 17M).
- Segmen Loyal dan Lost memiliki performa rendah → butuh strategi upselling.

🎯 Rekomendasi Strategis

🔹 1. Strategi untuk Low Order – High Value Customer
- Bundling produk premium
- Diskon eksklusif
- Personalisasi penawaran

🔹 2. Fokus pada Produk Pendapatan Tertinggi
- Prioritaskan stok Classic Cars
- Pastikan ready stock di negara pasar utama (USA)

🔹 3. Tingkatkan Loyalitas di Segmen Loyal & At Risk
- Program reward atau poin
- Cashback
- Pengiriman gratis
- Reminder berkala

🔹 4. Perbesar Skala Order
- Volume discount
- Paket bundling
- Loyalty tier system untuk pembelian besar
