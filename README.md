⚠️ Disclaimer Dataset

**Dataset dalam proyek ini merupakan dataset sintetis yang dibuat dengan
bantuan AI untuk tujuan pembelajaran dan demonstrasi analisis data.**

Dataset tidak merepresentasikan data operasional, pelanggan, transaksi,
maupun performa perusahaan logistik tertentu di dunia nyata.

Angka, nama courier, kota, transaksi, dan pola yang terdapat dalam dataset
tidak boleh dianggap sebagai data atau statistik aktual dari perusahaan
maupun wilayah tertentu.

Fokus proyek ini adalah menunjukkan proses **data cleaning, exploratory
data analysis (EDA), data visualization, dan business insight**, bukan
memberikan gambaran faktual mengenai industri logistik sebenarnya.

# 📦 Logistics Delivery Performance Analysis

## 📌 Ringkasan Proyek

Proyek ini merupakan analisis data pengiriman logistik yang bertujuan untuk
mengevaluasi performa pengiriman dan mengidentifikasi pola yang berkaitan
dengan keterlambatan pengiriman.

Analisis mencakup beberapa aspek, seperti:

- Performa courier
- Berat paket
- Biaya pengiriman
- Waktu pengiriman
- Rute pengiriman
- Kota asal dan tujuan
- Tipe pelanggan
- Status pengiriman

Tujuan utama proyek ini adalah mengubah data mentah menjadi insight yang
dapat membantu memahami pola performa pengiriman dan area yang perlu
diinvestigasi lebih lanjut.

---

## 🎯 Business Questions

Analisis ini dibuat untuk menjawab beberapa pertanyaan:

1. Bagaimana performa pengiriman secara keseluruhan?
2. Bagaimana performa pengiriman berbeda antar courier?
3. Apakah paket yang lebih berat lebih sering mengalami keterlambatan?
4. Rute dan kota tujuan mana yang memiliki tingkat keterlambatan lebih tinggi?
5. Apakah terdapat hubungan antara biaya pengiriman dan waktu pengiriman?
6. Apakah tipe pelanggan memiliki perbedaan performa pengiriman?

---

## 🛠️ Tools yang Digunakan

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

---

## 📊 Dataset

Dataset berisi informasi transaksi pengiriman logistik, dengan beberapa
variabel utama:

| Kolom | Deskripsi |
|---|---|
| `order_id` | ID unik order |
| `order_date` | Tanggal order |
| `courier` | Penyedia jasa pengiriman |
| `origin_city` | Kota asal pengiriman |
| `destination_city` | Kota tujuan pengiriman |
| `weight_kg` | Berat paket dalam kilogram |
| `shipping_cost` | Biaya pengiriman |
| `delivery_days` | Lama waktu pengiriman |
| `status` | Status pengiriman |
| `customer_type` | Tipe pelanggan |

Salah satu variabel turunan yang dibuat adalah `is_late`

Dataset awal terdiri dari sekitar 1.000+ baris data sebelum proses
data cleaning.
