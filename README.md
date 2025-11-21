# 📊 Statistics Python Playground

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Statistics](https://img.shields.io/badge/Statistics-Comprehensive-orange)

**Panduan Lengkap Statistik dengan Python untuk Pemula hingga Mahir**

[English](#) | [Bahasa Indonesia](#)

</div>

## 🎯 Tentang Repository Ini

Repository ini adalah sumber belajar komprehensif untuk memahami statistik menggunakan Python. Dibuat dengan pengalaman 25 tahun dalam bidang statistik dan pemrograman, repository ini menyediakan:

- ✅ Penjelasan teori statistik yang mendalam
- ✅ Code Python yang dapat dijalankan dan dimodifikasi
- ✅ Playground interaktif untuk setiap konsep
- ✅ Visualisasi data yang informatif
- ✅ Use case dunia nyata
- ✅ Dataset praktis untuk latihan

## 📚 Daftar Isi

### 1️⃣ **Statistik Deskriptif**
- [1.1 Measures of Central Tendency](./01_descriptive_statistics/01_central_tendency.ipynb)
- [1.2 Measures of Dispersion](./01_descriptive_statistics/02_dispersion.ipynb)
- [1.3 Measures of Shape](./01_descriptive_statistics/03_shape.ipynb)
- [1.4 Data Visualization](./01_descriptive_statistics/04_visualization.ipynb)

### 2️⃣ **Teori Probabilitas**
- [2.1 Basic Probability](./02_probability/01_basic_probability.ipynb)
- [2.2 Conditional Probability](./02_probability/02_conditional_probability.ipynb)
- [2.3 Bayes' Theorem](./02_probability/03_bayes_theorem.ipynb)
- [2.4 Counting Methods](./02_probability/04_counting_methods.ipynb)

### 3️⃣ **Distribusi Probabilitas**
- [3.1 Normal Distribution](./03_distributions/01_normal_distribution.ipynb)
- [3.2 Binomial Distribution](./03_distributions/02_binomial_distribution.ipynb)
- [3.3 Poisson Distribution](./03_distributions/03_poisson_distribution.ipynb)
- [3.4 Exponential Distribution](./03_distributions/04_exponential_distribution.ipynb)
- [3.5 Other Distributions](./03_distributions/05_other_distributions.ipynb)

### 4️⃣ **Sampling & Estimasi**
- [4.1 Sampling Methods](./04_sampling_estimation/01_sampling_methods.ipynb)
- [4.2 Central Limit Theorem](./04_sampling_estimation/02_central_limit_theorem.ipynb)
- [4.3 Point Estimation](./04_sampling_estimation/03_point_estimation.ipynb)
- [4.4 Confidence Intervals](./04_sampling_estimation/04_confidence_intervals.ipynb)

### 5️⃣ **Uji Hipotesis**
- [5.1 Hypothesis Testing Basics](./05_hypothesis_testing/01_basics.ipynb)
- [5.2 t-Tests](./05_hypothesis_testing/02_t_tests.ipynb)
- [5.3 Chi-Square Tests](./05_hypothesis_testing/03_chi_square.ipynb)
- [5.4 ANOVA](./05_hypothesis_testing/04_anova.ipynb)
- [5.5 Non-parametric Tests](./05_hypothesis_testing/05_nonparametric.ipynb)

### 6️⃣ **Korelasi & Regresi**
- [6.1 Correlation Analysis](./06_correlation_regression/01_correlation.ipynb)
- [6.2 Simple Linear Regression](./06_correlation_regression/02_simple_regression.ipynb)
- [6.3 Multiple Regression](./06_correlation_regression/03_multiple_regression.ipynb)
- [6.4 Logistic Regression](./06_correlation_regression/04_logistic_regression.ipynb)
- [6.5 Model Evaluation](./06_correlation_regression/05_model_evaluation.ipynb)

### 7️⃣ **Topik Lanjutan**
- [7.1 Time Series Analysis](./07_advanced/01_time_series.ipynb)
- [7.2 Multivariate Analysis](./07_advanced/02_multivariate.ipynb)
- [7.3 Bootstrapping](./07_advanced/03_bootstrapping.ipynb)
- [7.4 Monte Carlo Simulation](./07_advanced/04_monte_carlo.ipynb)

### 8️⃣ **Proyek Praktis**
- [8.1 A/B Testing](./08_projects/01_ab_testing.ipynb)
- [8.2 Customer Segmentation](./08_projects/02_customer_segmentation.ipynb)
- [8.3 Sales Forecasting](./08_projects/03_sales_forecasting.ipynb)
- [8.4 Quality Control](./08_projects/04_quality_control.ipynb)

## 🚀 Cara Menggunakan

### Instalasi

```bash
# Clone repository
git clone https://github.com/akababe/statistics-python-playground.git
cd statistics-python-playground

# Buat virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
# atau
venv\Scripts\activate  # Windows

# Install dependencies
pip install -r requirements.txt

# Jalankan Jupyter Notebook
jupyter notebook
```

### Struktur File

```
statistics-python-playground/
├── 01_descriptive_statistics/
├── 02_probability/
├── 03_distributions/
├── 04_sampling_estimation/
├── 05_hypothesis_testing/
├── 06_correlation_regression/
├── 07_advanced/
├── 08_projects/
├── datasets/
├── utils/
├── requirements.txt
└── README.md
```

## 📦 Dependencies

```python
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
seaborn>=0.11.0
scipy>=1.7.0
scikit-learn>=0.24.0
statsmodels>=0.13.0
jupyter>=1.0.0
plotly>=5.0.0
```

## 🎓 Cara Belajar

1. **Mulai dari Dasar**: Ikuti urutan topik dari 1 hingga 8
2. **Praktik Langsung**: Jalankan setiap cell di Jupyter Notebook
3. **Eksperimen**: Ubah parameter dan variabel untuk memahami dampaknya
4. **Visualisasi**: Perhatikan grafik dan interpretasinya
5. **Use Case**: Pahami penerapan di dunia nyata

## 💡 Fitur Playground

Setiap notebook dilengkapi dengan:

```python
# 🎮 PLAYGROUND ZONE
# Ubah nilai di bawah ini dan jalankan ulang untuk melihat hasilnya

sample_size = 100  # Coba: 50, 500, 1000
mean_value = 50    # Coba: 30, 70, 100
std_dev = 10       # Coba: 5, 15, 20
```

## 📊 Dataset

Repository ini menyertakan dataset untuk praktik:

- `sales_data.csv` - Data penjualan
- `customer_data.csv` - Data pelanggan
- `quality_control.csv` - Data kontrol kualitas
- `marketing_campaign.csv` - Data kampanye marketing
- `stock_prices.csv` - Data harga saham

## 🤝 Kontribusi

Kontribusi sangat diterima! Silakan:

1. Fork repository ini
2. Buat branch baru (`git checkout -b feature/AmazingFeature`)
3. Commit perubahan (`git commit -m 'Add some AmazingFeature'`)
4. Push ke branch (`git push origin feature/AmazingFeature`)
5. Buat Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📧 Kontak

Akababe - [@akababe](https://github.com/akababe)

Project Link: [https://github.com/akababe/statistics-python-playground](https://github.com/akababe/statistics-python-playground)

## 🙏 Acknowledgments

- Python Software Foundation
- NumPy, Pandas, Matplotlib, Seaborn communities
- SciPy and Statsmodels contributors
- Komunitas data science Indonesia

---

<div align="center">

**⭐ Jika repository ini membantu, jangan lupa beri star! ⭐**

Made with ❤️ by Statistics Enthusiasts

</div>