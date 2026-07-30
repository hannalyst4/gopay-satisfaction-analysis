# GoPay-Satisfaction-Analysis
Analisis tingkat kepuasan pengguna aplikasi GoPay menggunakan Google Colab, Google sheets dan Google Looker Studio

*Dataset:* Dataset diperoleh dengan pendekatan kuantitatif kuesioner skala Likert (1-4)                                                    
*Tools:* Google Colab dan Google Sheets untuk proses EDA dan Google Looker Studio untuk visualisai

---

## Dashboard Overview & Architecture
*Dashboard* ini dirancang dalam satu halaman yang memuat beberapa komponen utama:
1. **Scorecard:** Menampilkan total responden dan skor rata-rata kepuasan keseluruhan.
2. **Interactive Filter:** Menu *drop-down* berbasis **Jenis Kelamin** untuk melakukan *filtering* data secara dinamis.
3. **Demographic Analysis (Donut Chart):** Visualisasi proporsi profil responden berdasarkan *Jenis Kelamin*, *Kelompok Usia*, dan *Frekuensi Penggunaan*.
4. **Performance Matrix (Bar Chart):** Perbandingan rata-rata skor pada 5 dimensi utama penilaian aplikasi.
5. **Cross-Tabulation Table:** Analisis perbandingan tingkat kepuasan rata-rata berdasarkan kelompok usia.
6. **Link:** https://datastudio.google.com/reporting/d88f465a-7006-4d69-92de-54a4908d1c4a/page/XdB5F

---

## Key Insights

Berdasarkan analisis data dari **111 responden**, berikut adalah temuan krusial yang berhasil diekstrak dari *dashboard*:
### 1. Profil & Perilaku Pengguna
Sebagian besar responden didominasi oleh kelompok usia muda **17 - 29 tahun (92,8%)** dengan mayoritas pengguna berjenis kelamin **Perempuan (74,8%)**. Sedangkan untuk frekuensi penggunaan aplikasi tergolong cukup aktif. Sebanyak **40,5%** responden menggunakan aplikasi secara rutin (5–15 kali sebulan), diikuti oleh pengguna kategori jarang (38,7%) dan sangat sering (20,7%).
### 2. Evaluasi Dimensi Layanan 
Aspek **Kemudahan Penggunaan ($X_1$)**, **Keamanan Transaksi ($X_2$)**, dan **Kecepatan Aplikasi ($X_5$)** menjadi pilar utama kepuasan dengan rata-rata skor stabil di kisaran **3,50 – 3,53**.Namun untuk aspek **Kualitas Layanan ($X_4$)** mmperoleh skor terendah di angka **3,28**. 
### 3. Tingkat Kepuasan Berdasarkan Kelompok Usia
Secara keseluruhan, rata-rata tingkat kepuasan (*Y_Kepuasan*) berada di angka **3,58 / 4,00** (kategori sangat puas). Kelompok usia >45 tahun memberikan skor kepuasan tertinggi (4,00), meskipun populasinya kecil, sementara kelompok usia produktif utama (17–29 tahun) berada di angka 3,55.

---

## Actionable Insights
Berdasakan key insights yang diperoleh, ada beberapa hal yang bisa dilakukan oleh pihak GoPay:
1. **Optimalisasi Layanan Pelanggan:** Mengingat skor Kualitas Layanan ($X_4$) paling rendah dibanding dimensi lain, perusahaan disarankan mempercepat respons *help-center* dan memperjelas alur resolusi kendala pengguna.
2. **Pertahankan Performa Teknologi:** Stabilitas pada aspek Kemudahan Penggunaan ($X_1$) dan Keamanan ($X_2$) harus terus dijaga agar retensi pengguna di rentang usia 17–29 tahun tetap tinggi.
