[![Hugging Face Spaces](https://img.shields.io/badge/🤗%20HuggingFace-Spaces-blue)](https://huggingface.co/spaces/<username>/<space-name>)
[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)

📓 [Klik untuk buka notebook utama](./bismillah_produktif.ipynb)

# 💻 Mitigasi Downtime Industri melalui Prediksi Kegagalan Mesin

Notebook ini membangun model klasifikasi untuk **memprediksi kegagalan mesin** menggunakan dataset [AI4I 2020 Predictive Maintenance](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset) dari UCI Machine Learning Repository.

Tujuan utama dari proyek ini adalah membantu sektor industri dalam **mengurangi downtime tak terduga** dengan melakukan deteksi dini terhadap kemungkinan kegagalan mesin melalui pendekatan Machine Learning.

## 🧠 Fitur Utama

- Preprocessing otomatis untuk data numerik & kategorikal
- Penanganan imbalance menggunakan:
  - SMOTE
  - SMOTEENN
  - SMOTETomek
- Model yang digunakan:
  - Random Forest
  - XGBoost
- Evaluasi model dengan:
  - Confusion Matrix
  - Classification Report
  - ROC-AUC & PR-AUC
  - Visualisasi Feature Importance

## 📂 Struktur Notebook

- `bismillah-produktif.ipynb` – Notebook utama berisi seluruh pipeline
- `requirements.txt` – Daftar dependensi tambahan jika diperlukan

## 📦 Dependensi Utama

- `pandas`, `scikit-learn`, `imbalanced-learn`
- `matplotlib`, `seaborn`
- `xgboost`
- `ucimlrepo` untuk fetch dataset dari UCI

## 🚀 Cara Menjalankan

1. Buka tab **"App"** di atas untuk mengakses JupyterLab
2. Klik dan buka file `bismillah_produktif.ipynb`
3. Jalankan sel-selnya secara berurutan dari atas ke bawah
4. Analisis visual akan muncul secara interaktif di output

## 📊 Dataset

- **Nama**: AI4I 2020 Predictive Maintenance Dataset  
- **Sumber**: [UCI Repository](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset)  
- **Jenis**: Data sintetik (realistik), multivariate time-series  
- **Target**: Kegagalan mesin (0: Tidak Gagal, 1: Gagal)

## 👩‍💻 Author

- Hana Azizah Nurhadi
- Hikmia Sofia Nur Izzati
- Mazaya Khairana Nariswari

---

> 🐳 Dibuat sebagai demonstrasi notebook interaktif menggunakan Hugging Face Spaces (JupyterLab).
