# Repository Praktikum Pembelajaran Mesin (INF62325)

**Nama** : Ibrahim Hilal  
**NIM**  : 2488010030
**Kelas**: Informatika - C

---

## Daftar Berkas Praktikum

### 1. Persiapan Awal & Cek Versi Pustaka
- **Nama Berkas:** `PM_TuRi1_EDA_Ibrahim_Hilal.ipynb`
- **Deskripsi:** Pengecekan dan verifikasi lingkungan kerja Google Colab serta pencatatan versi pustaka Python utama (`scikit-learn`, `pandas`, `numpy`, `matplotlib`).

### 2. Modul Demo & Latihan Pertemuan 2 (Jenis Pembelajaran & Alur Kerja ML)
- **Nama Berkas:** `PM_P2_Ibrahim_Hilal.ipynb`
- **Deskripsi:** 
  - Mengenali struktur data (instans, fitur, dan label).
  - Membedakan tugas **Klasifikasi** dan **Regresi** berdasarkan tipe data label.
  - Mempraktikkan pembagian data latih (*training*) dan data uji (*testing*) menggunakan `train_test_split`.
  - Mengerjakan latihan mandiri (DataFrame siswa, pembagian data $test\_size=0.2$, dan studi kasus prediksi pengunjung toko).
  - Mengisi jawaban refleksi alur kerja ML.

---

## Temuan Utama & Catatan
- **Klasifikasi vs Regresi:** Kasus prediksi label numerik kontinu (seperti harga rumah atau jumlah pengunjung toko) menggunakan teknik Regresi, sedangkan label berupa kategori/diskrit (seperti status "Lulus/Tidak") menggunakan Klasifikasi.
- **Data Latih & Uji:** Pembagian data uji disembunyikan saat proses pelatihan untuk menguji kemampuan generalisasi model terhadap data baru secara objektif.
