# Project Capstone Hactiv8 - Global Inflation Analysis

## **Project Overview**
Proyek ini bertujuan untuk menganalisis data inflasi global menggunakan dataset `global_inflation_data.csv`.  
Analisis meliputi tren inflasi per negara, pengelompokan kategori inflasi, serta pembuatan ringkasan kondisi inflasi global.  
Proses analisis dilakukan di **Google Colab** dan didukung oleh **model AI IBM Granite 3.3-8b-Instruct** untuk membantu klasifikasi dan pembuatan ringkasan.

---

## **Raw Dataset Link**
Dataset yang digunakan:
- **Nama File:** `global_inflation_data.csv`
- **Link Dataset:** (https://www.kaggle.com/datasets/sazidthe1/global-inflation-data)

---

## **Insight & Findings**
1. **Tren Inflasi Tahunan:**  
 - Beberapa negara menunjukkan tren inflasi **meningkat tajam** dalam 5 tahun terakhir.
 - Ada negara dengan inflasi **stabil rendah (<3%)**, namun sebagian besar negara berkembang cenderung memiliki inflasi **moderate hingga tinggi**.

2. **Kategori Inflasi:**  
 - Negara dikategorikan dalam lima kelompok:
   - **Deflation**
   - **Low (<3%)**
   - **Moderate (3-7%)**
   - **High (7-20%)**
   - **Very High (>20%)**

3. **Insight Global:**  
 - Inflasi tinggi sebagian besar terjadi di kawasan dengan volatilitas ekonomi.
 - Rekomendasi kebijakan yang dihasilkan AI:
   - Fokus pada **stabilisasi harga pangan dan energi**.
   - **Koordinasi kebijakan moneter** antar negara.
   - **Penguatan cadangan devisa** untuk menghadapi ketidakpastian global.

---

## **AI Support Explanation**
Proyek ini memanfaatkan **IBM Granite 3.3-8b-Instruct (Large Language Model)** melalui **Replicate API** untuk:
- **Klasifikasi otomatis:**  
Mengelompokkan negara berdasarkan tingkat inflasi dan tren (increasing, decreasing, stable, volatile).
- **Ringkasan otomatis:**  
Menyusun **insight global** dan **rekomendasi kebijakan** berdasarkan hasil analisis data mentah.

Penggunaan AI membantu mempercepat proses analisis dengan:
- **Mengurangi bias manual** dalam klasifikasi.
- **Menyediakan ringkasan yang lebih komprehensif** berdasarkan data yang diproses.

---


