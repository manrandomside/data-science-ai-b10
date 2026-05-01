<div align="center">

# Data Science — AI Development B10

Kumpulan tugas dan praktikum Data Science yang dikerjakan selama mengikuti program **AI Development B10** di **Infinite Learning**.

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)](https://numpy.org/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat-square)](https://seaborn.pydata.org/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Active-success?style=flat-square)]()

</div>

---

## Table of Contents

- [About](#about)
- [Author](#author)
- [Tech Stack](#tech-stack)
- [Daftar Tugas](#daftar-tugas)
  - [Tugas 7 — Exploratory Data Analysis](#tugas-7--exploratory-data-analysis)
  - [Tugas 8 — Praktikum Data Science](#tugas-8--praktikum-data-science)
- [Struktur Repository](#struktur-repository)
- [Cara Menjalankan](#cara-menjalankan)
- [Workflow Pengerjaan](#workflow-pengerjaan)
- [Lisensi](#lisensi)

---

## About

Repository ini berisi penugasan mandiri yang dikerjakan untuk memenuhi syarat program AI Development B10 di Infinite Learning. Setiap tugas mencakup proses lengkap dari pengumpulan data, pembersihan, eksplorasi, visualisasi, sampai analisis dan penarikan insight.

Fokus utama dari setiap penugasan adalah memahami workflow Data Science secara end-to-end menggunakan tools Python (Pandas, NumPy, Matplotlib, Seaborn) dan Jupyter Notebook.

---

## Author

**Firman Fadilah**

- Role: Design Researcher & Scrum Master, Tim Kaca Digital Nusantara (KDN)
- Program: AI Development B10 — Infinite Learning
- Capstone Project: [Pangan Pintar](#) — Platform prediksi harga pangan strategis Indonesia berbasis AI

---

## Tech Stack

| Kategori | Tools |
|---|---|
| **Language** | Python 3.x |
| **Environment** | Jupyter Notebook (Google Colab) |
| **Data Manipulation** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Version Control** | Git, GitHub |

---

## Daftar Tugas

### Tugas 7 — Exploratory Data Analysis

Eksplorasi data COVID-19 global menggunakan dataset Worldometer untuk memahami pola penyebaran, tingkat kematian, recovery rate, dan strategi testing antar negara.

**Dataset:** [COVID-19 Worldometer](https://www.kaggle.com/datasets/imdevskp/corona-virus-report) (Kaggle)

**Cakupan:**
- Analisis distribusi kasus, kematian, dan kesembuhan
- Analisis per benua
- Positivity rate analysis
- Death rate vs Recovery rate
- Serious/Critical case analysis
- Top 10 negara dengan performa terbaik dan terburuk
- Correlation matrix antar variabel numerik

**File:** [`Tugas-7-EDA/Tugas7_EDA_FirmanFadilah.ipynb`](./Tugas-7-EDA/Tugas7_EDA_FirmanFadilah.ipynb)

---

### Tugas 8 — Praktikum Data Science

Praktikum end-to-end Data Science menggunakan dataset Housing Prices untuk memahami workflow lengkap dari preprocessing sampai feature engineering.

**Dataset:** [Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset) (Kaggle)

**Cakupan:**
- Cek missing values dan duplicate
- Handling missing values dan duplicate
- Transformasi data kategorik ke numerik
- Exploratory Data Analysis dengan visualisasi
- Correlation matrix
- Feature Engineering (price_per_area, total_rooms)

**File:** [`Tugas-8-DataScience/Tugas_8_DataScience_FirmanFadilah.ipynb`](./Tugas-8-DataScience/Tugas_8_DataScience_FirmanFadilah.ipynb)

---

## Struktur Repository

```
data-science-ai-b10/
├── Tugas-7-EDA/
│   └── Tugas7_EDA_FirmanFadilah.ipynb
├── Tugas-8-DataScience/
│   └── Tugas_8_DataScience_FirmanFadilah.ipynb
├── .gitignore
├── LICENSE
└── README.md
```

---

## Cara Menjalankan

### Opsi 1 — Google Colab (Recommended)

1. Buka file `.ipynb` di GitHub
2. Klik tombol "Open in Colab" atau salin URL ke [Google Colab](https://colab.research.google.com/)
3. Upload dataset yang dibutuhkan ke session Colab
4. Run All

### Opsi 2 — Local

```bash
# Clone repository
git clone https://github.com/manrandomside/data-science-ai-b10.git
cd data-science-ai-b10

# Install dependencies
pip install pandas numpy matplotlib seaborn jupyter

# Jalankan Jupyter
jupyter notebook
```

---

## Workflow Pengerjaan

Setiap tugas dikerjakan secara bertahap dengan workflow Git yang terstruktur:

1. **Setup** — inisialisasi struktur folder dan template kosong
2. **Implementasi bertahap** — setiap section dikerjakan dalam commit terpisah
3. **Insight & dokumentasi** — penambahan analisis dan kesimpulan
4. **Final review** — pengecekan akhir dan finalisasi

Pendekatan ini bertujuan untuk menjaga history yang rapi dan mudah ditelusuri, sekaligus mensimulasikan workflow tim development di dunia nyata.

**Convention commit message** yang digunakan:
- `feat:` untuk penambahan kode/fitur baru
- `docs:` untuk dokumentasi dan insight
- `chore:` untuk setup dan konfigurasi
- `refactor:` untuk perbaikan struktur tanpa mengubah fungsi

---

## Lisensi

Repository ini menggunakan lisensi MIT — lihat file [LICENSE](./LICENSE) untuk detail.

---

<div align="center">

**Made with care by Firman Fadilah**

Part of AI Development B10 program at [Infinite Learning](https://infinitelearning.id/)

</div>
