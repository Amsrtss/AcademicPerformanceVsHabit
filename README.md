# 🎓 Student Habits vs Academic Performance Prediction

Aplikasi interaktif berbasis Streamlit untuk memprediksi skor ujian mahasiswa berdasarkan kebiasaan harian seperti jam belajar, kehadiran, tidur, penggunaan media sosial, dan lainnya. Proyek ini menggunakan Linear Regression dan dataset dari [Kaggle](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance).

---

## 📊 Fitur Utama

- Menampilkan dataset asli dan hasil preprocessing
- Visualisasi evaluasi model regresi
- Form interaktif untuk prediksi skor akhir mahasiswa
- Model dapat dipakai langsung oleh pengguna dengan input kebiasaan harian

---

## 📁 Struktur Proyek

```

├── app.py                      # Aplikasi Streamlit
├── train\_model.py             # Script pelatihan dan evaluasi model
├── preprocessing.ipynb        # Notebook preprocessing data
├── data.csv                   # Dataset mentah dari Kaggle
├── df\_encoded.csv             # Dataset setelah encoding
├── linear\_regression\_model.pkl # Model terlatih
├── scaler.pkl                 # Scaler data
├── evaluation\_results.pkl     # Hasil evaluasi model
├── requirements.txt           # Daftar pustaka Python
└── README.md                  # Dokumentasi proyek ini

````

---

## 🚀 Cara Menjalankan Aplikasi

1. **Clone repositori:**

```bash
git clone https://github.com/Amsrtss/AcademicPerformanceVsHabit.git
cd AcademicPerformanceVsHabit
````

2. **Install dependencies:**

```bash
pip install -r requirements.txt
```

3. **Jalankan aplikasi Streamlit:**

```bash
streamlit run app.py
```

---

## 🔬 Proses Model

* **Preprocessing:**

<img width="563" height="594" alt="image" src="https://github.com/user-attachments/assets/b036f721-eef3-4d3d-9be9-ad71854ea7f2" />
<img width="940" height="244" alt="image" src="https://github.com/user-attachments/assets/e5855624-a371-430f-b583-0c357909fe14" />
<img width="940" height="450" alt="image" src="https://github.com/user-attachments/assets/b45a8bb9-1355-4fd0-bb32-de20c2eaef0c" />

  * Deteksi dan penanganan missing value
  * Encoding ordinal dan nominal
  * Standarisasi fitur numerik
* **Modeling:**
<img width="866" height="380" alt="image" src="https://github.com/user-attachments/assets/1b32afc4-0f9a-465e-9d69-37c9648f1db4" />
<img width="743" height="300" alt="image" src="https://github.com/user-attachments/assets/e6816367-7122-47ba-955b-2a98876f0a53" />

  * Linear Regression
  * Split data: 72% train, 8% validation, 20% test
  * Evaluasi menggunakan MSE dan R²
* **Deployment:**

<img width="939" height="475" alt="image" src="https://github.com/user-attachments/assets/425d1bed-80b9-4931-8f97-0333cadcbff2" />
<img width="939" height="481" alt="image" src="https://github.com/user-attachments/assets/563ef4e4-d34b-4870-b68f-ff9feb167c7a" />

<img width="939" height="455" alt="image" src="https://github.com/user-attachments/assets/95832f37-d21e-4b57-bac7-6dbf7eb94ddf" />

  * Aplikasi Streamlit untuk demo prediksi interaktif

---

## 📈 Hasil Evaluasi Model
<img width="939" height="480" alt="image" src="https://github.com/user-attachments/assets/1a4e5ae2-513b-4b6c-813a-d93c3972e433" />

| Dataset    | MSE              | R² |
| ---------- | ---------------- | -- |
| Validation | Tertampil di app |    |
| Test       | Tertampil di app |    |

*Hasil evaluasi akan muncul otomatis saat aplikasi dijalankan.*

---

## 📄 Lisensi

MIT License. Silakan gunakan dan modifikasi proyek ini sesuai kebutuhan.


