# 📊 E-Commerce Cohort Analysis – User Retention Insight

## 📌 Project Overview

- **Business Problem**  
  E-commerce company mengalami tantangan dalam mempertahankan pengguna jangka panjang. Tingkat churn tinggi dalam bulan pertama setelah user sign-up menjadi masalah utama. Analisis cohort dilakukan untuk mengidentifikasi pola retensi dan perilaku pembelian berulang berdasarkan waktu akuisisi user.

- **Objective**  
  Menyediakan insight berbasis data mengenai retensi user dari berbagai cohort untuk mendukung pengambilan keputusan tim produk & marketing dalam meningkatkan customer lifetime value (CLV).

- **Dataset**  
  - Sumber: Sample transaksi e-commerce  
  - Ukuran: ±10.000 transaksi  
  - Periode: Jan–Dec 2011

- **Tools & Tech**  
  - 🐍 Python (Pandas, Matplotlib, Seaborn)  
  - 📊 Cohort heatmap visualization  
  - 📝 Google Colab (Notebook link below)

---

## 🔍 Methodology

1. **Data Preparation**
   - Load dataset transaksi, parsing `order_date` dan `user_id`
   - Generate `cohort_month` dan `cohort_index` untuk tiap user

2. **Cohort Grouping & Retention Calculation**
   - User dikelompokkan berdasarkan bulan pertama melakukan transaksi
   - Hitung persentase user yang tetap melakukan transaksi di bulan ke-n

3. **Visualization**
   - Buat heatmap retention matrix untuk mengidentifikasi trend secara visual

---

## 📈 Analysis Results

- **🔑 Key Finding:**  
  - Sebagian besar cohort kehilangan lebih dari 70% penggunanya setelah bulan pertama
  - Hanya 8–15% user yang tetap aktif hingga bulan ke-6
  - Cohort Desember 2010 menunjukkan retensi terbaik hingga bulan ke-11 dengan puncak 50% pada bulan ke-10

- **💼 Business Impact:**  
  - Tanpa strategi onboarding dan engagement yang kuat, potensi revenue dari user jangka panjang hilang
  - Insight ini membuka peluang untuk eksperimen campaign retargeting dan program loyalitas bagi cohort awal

---

## ✅ Conclusion & Recommendations

- **💡 How to Improve**
  - Optimalkan strategi onboarding (welcome email, edukasi produk)
  - Identifikasi kanal akuisisi terbaik dari cohort yang memiliki retensi tinggi
  - Terapkan loyalty program berbasis waktu (contoh: diskon untuk repeat buyer dalam 30 hari pertama)

- **🚧 Challenges**
  - Data tidak menyertakan kanal akuisisi dan kategori produk
  - Tidak tersedia data tambahan seperti frekuensi pembelian atau AOV (average order value) untuk segmentasi lebih lanjut

---

## 📂 Project Files & Demo

- 📓 [View Full Analysis Notebook on Colab](https://colab.research.google.com/drive/1hoKQflbXP8e8pdS5fIDFFBxetsPZ6B74?usp=sharing)  
- 📸 ![Cohort Retention Heatmap](output/cohort_heatmap.png)  
- 📁 [Dataset (if available)](data/ecommerce_sample.csv)

---

## 🙋🏻‍♀️ About Me

**Lia Amalia** – IT Business Analyst pivoting into Data & BI Analyst roles.  
📍 Jakarta | 💼 SQL, Python, BI Tools  
📫 [LinkedIn](https://linkedin.com/in/kiaamalia) |

---

> Data without action is just numbers. But insight-driven strategy is the key to customer success. 🚀
