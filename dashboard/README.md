
## 🇬🇧 EN

## 📁 File Overview

- **Retail_Sales_Performance_Dashboard.xlsx**  
  Main Excel file containing the dashboard, analytical pivots, helper calculations, and datasets.

---

## 🧩 Excel Sheet Structure & Purpose

### 1. **Dashboard** (Main Sheet)
The primary visualization layer of the project.

This sheet presents:
- Key Performance Indicators (KPIs)
- Revenue trends and growth analysis
- Product, store, and seasonal performance
- Interactive slicers for dynamic filtering

The dashboard is designed to support **high-level business decision-making**, enabling users to quickly identify performance patterns and potential issues.

---

### 2. **Dashboard_Pivots**
This sheet contains **all Pivot Tables and Pivot Charts** used as data sources for the dashboard.

Purpose:
- Acts as the analytical backbone of the dashboard
- Ensures separation between calculations and presentation
- Allows easier maintenance and scalability of the dashboard

All dashboard visuals are directly linked to these pivots.

---

### 3. **Helper_Sheet**
This sheet is used for **supporting calculations and intermediate logic** that are not suitable to be placed directly inside pivot tables.

Typical use cases include:
- Custom aggregations
- Conditional calculations
- Derived metrics required for specific visualizations

This approach keeps the dashboard clean while preserving analytical flexibility.

---

### 4. **Dataset Sheets**
The raw data layer of the project, structured in a relational format.

#### a. **customer_data**
Contains customer-level information used to support segmentation and transaction analysis.

#### b. **sales_data**
The central fact table containing transaction-level records, including:
- Revenue values
- Discounts
- Returns
- Transaction validity indicators

This sheet serves as the **primary analytical driver** of the dashboard.

#### c. **product_data**
Contains product attributes used to analyze:
- Product-level revenue contribution
- Quantity sold
- Seasonal categorization

#### d. **store_data**
Contains store-level information used for:
- Store performance comparison
- Revenue contribution analysis
- Pareto-based store filtering (80/20 principle)

---

## 🔄 Analytical Workflow

1. Raw datasets are stored in dedicated dataset sheets.
2. Relationships and calculations are handled via Power Pivot and helper logic.
3. Pivot tables aggregate metrics required for analysis.
4. The dashboard consumes these pivots to present insights in an interactive format.

This layered structure mirrors a **standard analytical pipeline**, even though it is implemented entirely within Excel.

---

## ⚠️ Notes

- The dataset used in this project is **synthetic** and intended for educational and portfolio purposes.
- The dashboard is optimized for desktop viewing.

---

# 🇮🇩 ID

## 📁 Ringkasan File

Folder ini berisi **deliverable utama analisis**, yaitu dashboard performa penjualan retail yang dibangun menggunakan **Microsoft Excel dan Power Pivot**.

Struktur file Excel dirancang untuk memisahkan dengan jelas **data mentah, logika analisis, pivot, dan visualisasi akhir**, sehingga mencerminkan alur kerja analisis yang rapi dan terstruktur.

---

## 🧩 Struktur & Fungsi Sheet Excel

### 1. **Dashboard** (Sheet Utama)
Merupakan lapisan visualisasi utama dari proyek ini.

Sheet ini menampilkan:
- Key Performance Indicators (KPI)
- Analisis tren dan pertumbuhan revenue
- Performa produk, toko, dan musiman
- Slicer interaktif untuk eksplorasi data

Dashboard dirancang untuk mendukung **pengambilan keputusan berbasis bisnis**, bukan sekadar pelaporan statis.

---

### 2. **Dashboard_Pivots**
Berisi seluruh **Pivot Table dan Pivot Chart** yang digunakan sebagai sumber data dashboard.

Fungsi utama:
- Menjadi tulang punggung analisis
- Memisahkan logika perhitungan dari tampilan visual
- Mempermudah pemeliharaan dan pengembangan dashboard

---

### 3. **Helper_Sheet**
Digunakan untuk **perhitungan pendukung dan logika antara** yang tidak ideal jika ditempatkan langsung di pivot table.

Contoh penggunaan:
- Perhitungan khusus
- Logika kondisional
- Metric turunan untuk kebutuhan visualisasi tertentu

Pendekatan ini menjaga dashboard tetap bersih tanpa mengorbankan fleksibilitas analisis.

---

### 4. **Sheet Dataset**
Lapisan data mentah yang disusun secara relasional.

#### a. **customer_data**
Berisi informasi pelanggan yang mendukung analisis segmentasi dan transaksi.

#### b. **sales_data**
Merupakan tabel fakta utama yang mencakup:
- Nilai penjualan
- Diskon
- Return
- Indikator validitas transaksi

Sheet ini menjadi **penggerak utama seluruh analisis**.

#### c. **product_data**
Berisi atribut produk untuk analisis:
- Kontribusi revenue per produk
- Jumlah unit terjual
- Kategori musiman produk

#### d. **store_data**
Berisi informasi toko untuk:
- Perbandingan performa antar toko
- Analisis kontribusi revenue
- Filter toko berbasis prinsip Pareto (80/20)

---

## 🔄 Alur Analisis

1. Dataset disimpan pada sheet terpisah.
2. Relasi dan perhitungan dilakukan melalui Power Pivot dan helper logic.
3. Pivot table digunakan untuk agregasi metrik.
4. Dashboard menyajikan insight secara interaktif berdasarkan pivot tersebut.

Struktur ini merepresentasikan **pipeline analisis standar**, meskipun seluruh proses dilakukan di Excel.

---

## ⚠️ Catatan

- Dataset bersifat **sintetis** dan digunakan untuk keperluan pembelajaran serta portofolio.
- Dashboard dioptimalkan untuk tampilan desktop.
