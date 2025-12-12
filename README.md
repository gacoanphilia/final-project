# FINAL PROJECT SEMESTER GASAL 2025/2026
**DEPARTEMEN STATISTIKA** | **FAKULTAS SAINS DAN ANALITIKA DATA** | **INSTITUT TEKNOLOGI SEPULUH NOPEMBER**

**Program Studi**: S1-Sains Data

**Mata Kuliah**: Teknik Sampling dan Data Wrangling A (SD234304)

**Dosen Pengampu**:
1. Dr. Dra. Agnes Tuti Rumiati, M.Sc.
2. Neni Alya Firdausanti, S.Si., M. Stat., Ph.D.
3. Husna Mir'atin Nuroini, S.Stat., M.Stat.

**Anggota Kelompok 5**:
1. Dewa Putra Yuda (5052241012)
2. Marvelio Jonathan Wijaya (5052241017)
3. Riska Karina Tarigan (5052241028)
4. Shafa Agnia Ramadhan (5052241029)

= : >< : = : >< : =

## Analisis Dataset NFL (2000-2019)

### Temuan Utama:

#### 1. Paradoks Produktivitas
Meskipun rata-rata skor pertandingan NFL terus meningkat dari tahun ke tahun, ternyata rata-rata kehadiran penonton tidak berkembang! Ini menjadi indikasi kualitas pertandingan tidak menaikkan penjualan tiket.

#### 2. Pola Kemenangan - Keseimbangan adalah Hal Utama
Visualisasi *Strategic Map* kami menunjukkan bahwa Juara Superbowl hampir selalu berada di kuadran pemain yang dikategorikan "Elite Balanced" dalam istilah *football*. Pembeda utamanya bukan hanyalah total kemenangan, namun *turnover margin* (+0.78 per game untuk juara) dan **SRS Rating (>6.0)**.

#### 3. Faktor Lingkungan mendominasi Faktor Sosial
Hasil analisis data kami menggagalkan kebenaran suatu dugaan bahwa "banyaknya penonton pasti menjamin kemenangan tuan rumah". Padahal, grafik menunjukkan korelasi datar/lemah antara *Crowd Size* dan *Margin of Victory*. Sebaliknya, faktor cuaca/bulan (fenomena 'The Winter Freeze') memiliki dampak! Yaitu skor menurun drastis di bulan Desember-Januari.

### Library dan Bahasa:
*Final Project* ini dikerjakan menggunakan **Python** dengan library & package berikut:
- **Pandas** (untuk manipulasi & penggabungan data),
- **Matplotlib & Seaborn** (untuk visualisasi data), dan
- **Jupyter Notebook** (*package* untuk analisis data).

## Cara Menjalankan/*Run* *Project*
1. **Clone repository ini:**
```bash
git clone https://github.com/gacoanphilia/final-project.git
```
2. **Install dependencies**
Pastikan **Python** sudah terinstall! Kemudian jalankan kode di bawah ini:
```bash
pip install -r requirements.txt
```
3. **Buka Notebook**
Jalankan/*run* file `.ipynb` untuk melihat proses analisis:
```bash
jupyter notebook final-project.ipynb
```

## Struktur Direktori
```
final-project/  
│  
├── data/  
|   ├── raw/                     # Dataset mentah  
|   |   ├── attendance.csv       # Data mentah kehadiran  
|   |   ├── games.csv            # Data mentah pertandingan  
|   |   ├── readme.md            # Deskripsi 3 data mentah  
|   |   └── standings.csv        # Data mentah klasemen  
|   |  
|   └── processed/               # Dataset setelah dibersihkan  
|       ├── nfl.csv              # Data hasil cleaning & merging  
|       └── readme.md            # Deskripsi data processed  
|  
├── notebooks/  
|   └── final-project.ipynb  # Notebook analisis utama  
|  
├── requirements.txt     # Daftar package Python yang digunakan  
└── README.md            # File yang menjelaskan final project
```
  
*Laporan ini disusun sebagai pemenuhan penugasan mata kuliah Teknik Sampling dan Data Wrangling (A).*