<img src="photo.png" width="140" align="right" alt="Steven"/>
**🇮🇩 Bahasa Indonesia** · [🇬🇧 English](README.en.md)

# Hai, saya Steven 👋



**Mahasiswa Sains Data UNESA (semester 3)** yang fokus pada machine learning dan deep learning untuk klasifikasi data tabular, gambar, dan teks.
Saya suka belajar hal baru lewat praktik langsung: yang penting jalan, efisien, dan hasilnya terukur.

📫 [LinkedIn](https://www.linkedin.com/in/steven-liwang-946866383) · 🎯 Terbuka untuk **magang** dan **proyek freelance** di bidang data science / machine learning

<br clear="right"/>
---

## 🔭 Yang sedang saya kerjakan
- Memperdalam Machine Learning (XGBoost), fine-tuning model vision (DINO) dan NLP bahasa Indonesia (IndoBERT, IndoBERTweet)
- Membuat dan menjelajahi proyek berbasis studi kasus yang bisa dibaca
- Belajar membawa model ke aplikasi (Streamlit, Docker)

---

## 🏆 Pengalaman Kompetisi Data Mining (Semester 3)

Tiga kompetisi data mining tingkat nasional, semuanya berbasis deep learning. Kode dan dataset tidak dipublikasikan sesuai aturan panitia, jadi di bawah ini saya tuliskan pendekatan dan temuan teknisnya.

| Kompetisi | Tugas | Pendekatan | Hasil |
|---|---|---|---|
| **INFEST** | Image classification | DINO (fine-tuning), penanganan class imbalance | Penyisihan, peringkat **31 dari 89 tim** · [Sertifikat](https://drive.google.com/file/d/16lxTXY2BjMiBvxsSUAWoTnHSHQS7RM8X/view?usp=sharing) |
| **DATASCAPE** | Image classification | DINO, dikerjakan **secara individu** (kompetisi tim) | Penyisihan |
| **Action UNESA** | Text classification | IndoBERT, IndoBERTweet, XLM-R | Penyisihan |

**Peran saya:** mengerjakan sebagian besar alur teknis, yaitu EDA, preprocessing, feature engineering, modelling, dan evaluasi. Di dua kompetisi tim, tugas penulisan laporan dipegang rekan satu tim.

### Temuan yang saya dapat
- **DINO > ResNet50** untuk klasifikasi gambar: representasi hasil pretraining sudah lebih kaya dari awal.
- **Fine-tuning > training dari nol.** Dengan data terbatas, perbedaannya jelas.
- **Backbone yang dibekukan penuh (frozen) kurang optimal.** Perlu membuka sebagian layer.
- **Class imbalance harus ditangani eksplisit.** Kalau dibiarkan, performa kelas minoritas jatuh.
- **IndoBERT unggul di bahasa formal, IndoBERTweet unggul di bahasa slang/media sosial.** Pemilihan model harus mengikuti ragam bahasa datanya.
- **XLM-R saya uji sebagian lalu tidak dipakai.** Prioritas akhirnya IndoBERT dan IndoBERTweet.

> Pelajaran terbesar: eksperimen yang terdokumentasi rapi lebih berharga daripada satu skor bagus.

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-Mahir-3776AB?logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Nyaman-4479A1?logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-Mahir-F05032?logo=git&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Nyaman-F7931E?logo=scikitlearn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-Menengah-EE4C2C?logo=pytorch&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Menengah-2496ED?logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-Menengah-FF4B4B?logo=streamlit&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-Dasar-FFD21E?logo=huggingface&logoColor=black)

**Alur kerja ML:** EDA → preprocessing → feature engineering → modelling → evaluasi
**Teknik:** supervised & unsupervised learning, transfer learning, fine-tuning, penanganan class imbalance

---

## 📁 Proyek Pilihan

### ⭐ Machine Learning Pipeline (IDCAMP × Dicoding)
[Dicoding-Indonesia-Bootcamp-Project](https://github.com/stevvvpy/Dicoding-Indonesia-Bootcamp-Project)
Proyek clustering dan klasifikasi yang disusun sistematis dan lolos penilaian reviewer, dengan **continuous integration**. Data yang dipakai sintetis, fokusnya pada kerapian alur dan praktik rekayasa.
`Python` `scikit-learn` `Clustering` `Classification` `CI`

### 🧮 Struktur Data dan Algoritma: Proyek Akhir
[Struktur-Data-dan-Algoritma](https://github.com/stevvvpy/Struktur-Data-dan-Algoritma)
Proyek akhir mata kuliah Struktur Data dan Algoritma, ditulis dengan Python. Data yang dipakai sintetis. Proyek ini menggunakan linked list untuk mencari hubungan antar target.

### 🎮 Number Guess (Python)
[Number-Guess](https://github.com/stevvvpy/Number-Guess)
Game tebak angka sederhana dengan Python. Dibuat untuk melatih logika dasar dan alur program.

### 📊 Dashboard Visualisasi Data
[dashboard_visualiate_data](https://github.com/stevvvpy/dashboard_visualiate_data)
Visualisasi data pelanggan menggunakan bahasa pemrograman Python dengan Streamlit sebagai tempat deploy.

### 🏠 Kaggle Learn: Housing Prices
[Housing-Prices-Competition-for-Kaggle-Learn-Users](https://github.com/stevvvpy/Housing-Prices-Competition-for-Kaggle-Learn-Users)
Regresi prediksi harga rumah. Model yang digunakan adalah model dengan skor tertinggi yaitu XGboost

---
## 💼 Freelance

Saya menerima proyek data skala kecil sampai menengah. Saya masih mahasiswa, jadi saya menjaga ruang lingkup tetap jelas dan rutin memberi kabar progres.

**Yang bisa saya bantu**
- **Pembersihan data dan EDA:** merapikan data tabular yang berantakan dan merangkumnya menjadi temuan yang jelas
- **Dashboard:** dashboard data interaktif dengan Python dan Streamlit
- **Model prediktif:** klasifikasi, regresi, dan clustering dengan scikit-learn dan XGBoost
- **Prototipe klasifikasi teks dan gambar:** fine-tuning model pretrained (IndoBERT, DINO)

**Cara kerja saya**
1. Kita sepakati dulu tujuan, data, dan hasil yang diharapkan.
2. Versi pertama yang berjalan saya kirim cepat, lalu kita perbaiki bersama.
3. Anda menerima kode yang rapi dan terdokumentasi, plus ringkasan hasil.

📩 Untuk memulai proyek, kirim pesan lewat [LinkedIn](https://www.linkedin.com/in/steven-liwang-946866383) dengan deskripsi singkat data dan tujuan Anda.

---
## 🎓 Pendidikan dan Pelatihan
- **S1 Sains Data, Universitas Negeri Surabaya** (2025–sekarang, semester 3)
- **IDCAMP × Dicoding (Semester 1–2):** supervised dan unsupervised machine learning · [Sertifikat](https://drive.google.com/drive/folders/1-LEiUgEaFJ1d5T3y-s93KRboi-m7ojgc?usp=sharing)

---

## 💼 Pengalaman
- **Finance Department Intern, Trans Studio Mall:** pencatatan dan penyortiran data barang lelang. Melatih ketelitian dan kerapian data.

---

## 📬 Kontak
Tertarik berkolaborasi, magang, atau proyek freelance? Hubungi saya lewat [LinkedIn](https://www.linkedin.com/in/steven-liwang-946866383).

