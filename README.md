# Data-Mining
# Wine Quality Classification — UTS Data Mining 2026/2027

Repositori ini berisi penyelesaian **Take Home Test UTS Data Mining** Program Studi D3 Statistika Terapan dan Komputasi, Universitas Negeri Semarang (UNNES).

## Informasi Mahasiswa
* **Nama:** Moelani Artagin's Simarmata
* **NIM:** 2404010007
* **Dosen Pengampu:** Nur Achmey Selgi Harwanti, M.Stat

---

## Ringkasan Metodologi
1. **Dataset:** Terdiri dari `data_training.csv` (857 baris) dan `data_testing.csv` (286 baris) dengan 11 fitur kimiawi.
2. **Evaluasi:** Menggunakan **Stratified 5-Fold Cross Validation** untuk mengatasi *class imbalance* pada target `quality`.
3. **Model Terpilih:** **Extra Trees Classifier** ($n\_estimators=300$) memberikan akurasi rata-rata CV sebesar **64.53%**.
4. **Deliverables:** File prediksi `hasilprediksi_[NIM].csv` (hanya kolom `Id` dan `quality`).

---

## Struktur Repositori
* `uts_data_mining.ipynb` : Notebook analisis lengkap beserta dokumentasi dan visualisasi.
* `hasilprediksi_[NIM].csv` : File hasil prediksi pada data testing.
* `README.md` : Dokumentasi utama repositori.
