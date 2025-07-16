# 🛒 Apriori Algorithm - Outdoor Rental Recommendation

Rekomendasi sewa barang outdoor berdasarkan *Market Basket Analysis* menggunakan algoritma Apriori.  
Project ini menganalisis data peminjaman alat-alat outdoor seperti tenda, matras, headlamp, sleeping bag, dll dan menemukan pola pembelian atau peminjaman barang yang sering terjadi bersamaan.

---

## 🚀 Fitur

✅ Membaca data Excel transaksi peminjaman  
✅ Mengubah data ke format list transaksi  
✅ Proses algoritma Apriori via `mlxtend`  
✅ Menampilkan rules: antecedents → consequents  
✅ Menghitung support, confidence, dan lift  
✅ Menampilkan rekomendasi human-friendly

---

## 📂 Struktur File

```bash
.
├── apyorii_pynb.py              # Script utama proses apriori
├── Data_Transaksi_Oktober_November.xlsx  # Dataset transaksi sewa
├── README.md
└── .venv/ (optional, virtual env)


## 📦 **Instalasi**

**Aktifkan virtual environment** (jika ada):

```bash
.venv\Scripts\activate  # Windows

## **Lalu Install Semua Dependensi Utama**
pip install **pandas** **openpyxl** **mlxtend**
