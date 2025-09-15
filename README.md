# Analisis Emisi CO₂ Kendaraan Bermotor & Rekomendasi Kebijakan Fiskal

## Repository Outline

1. README.md - Deskripsi umum proyek
2. Notebook.ipynb - Notebook utama analisis eksplorasi dan visualisasi
3. P0M1_zhaky_baridwan_triaji_dataset.csv - Dataset kendaraan dari Kaggle

## Problem Background

Sektor transportasi merupakan penyumbang signifikan emisi karbon di banyak negara. Kebijakan subsidi energi dan pajak kendaraan sering kali tidak berbasis pada data teknis seperti konsumsi bahan bakar dan emisi kendaraan. Hal ini berisiko menyebabkan pemborosan anggaran dan memperburuk dampak lingkungan.

Melalui analisis data kendaraan, proyek ini bertujuan mendukung pengambilan kebijakan fiskal yang lebih adil dan efisien dengan mempertimbangkan performa emisi CO₂ dari berbagai tipe dan merk kendaraan.

## Project Output

- Jupyter Notebook berisi analisis eksploratif, statistik deskriptif & inferensial
- Visualisasi interaktif di Tableau (dashboard) yang dapat diakses di [Emission-Based Vehicle Policy – Fiscal Reform Recommendation](https://public.tableau.com/app/profile/zhaky.triaji/viz/VehicleEmission_17526734388120/MainDashboard?publish=yes)
- Rekomendasi kebijakan berbasis data untuk subsidi energi & pajak kendaraan

## Data

- **Sumber**: [Kaggle - CO2 Emission by Vehicles](https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles)
- **Jumlah**: 7.385 baris data, 12 kolom
- **Fitur (kolom) penting**:
  - Make, Model, Vehicle Class, Engine Size, Cylinders
  - Fuel Type, Fuel Consumption (City, Hwy, Combined)
  - CO₂ Emissions (g/km)
- **Missing Values**: Tidak ditemukan
- Duplikasi: 1.103 baris dihapus sebelum analisis
- Mengganti value pada kolom `Fuel Type` dari kode bahan bakar menjadi nama bahan bakar yang direpresentasikan oleh masing-masing kode

## Method

- Statistik Deskriptif: Central Tendency, Varians, Outlier
- Statistik Inferensial: ANOVA (Fuel Type vs CO₂, Vehicle Class vs CO₂)
- Korelasi Pearson: Engine Size vs CO₂ Emissions
- Visualisasi: Boxplot, Scatter Plot, Bar Chart
- Penjabaran insight untuk mendukung kebijakan publik (subsidi/pajak)

## Stacks

- Bahasa: Python (Jupyter Notebook)
- Library: `pandas`, `numpy`, `scipy`, `matplotlib`, `seaborn`
- Visualisasi Interaktif: Tableau Public
- Pengolahan Data: Exploratory Data Analysis (EDA)

## Reference

- Dataset: https://www.kaggle.com/datasets/debajyotipodder/co2-emission-by-vehicles  
