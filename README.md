[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/6JPudsdG)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=12707600&assignment_repo_type=AssignmentRepo)
# Milestones 1

_Milestones ini dibuat guna mengevaluasi pembelajaran pada Hacktiv8 Data Science Fulltime Program khususnya pada Phase 0._

---

# Assignment Problems

Kamu adalah seorang Data Analyst yang akan mengerjakan projek besar untuk menyelesaikan suatu permasalahan client dan client kamu butuh sekali hasil analisa datamu menggunakan statistik dan dashboard visualisasi data untuk membantu mereka menyelesaikan masalah.

---

# Assignment Instructions
## General Instructions
1. Pilihlah satu topik **bebas** dan buat **problem statement** terlebih dahulu menggunakan metode SMART.

2. Dataset dibebaskan dari sumber manapun (BigQuery, Kaggle, BPS, dll.) dan berformat apapun (csv, excel, json, sql query, dll.) **NOTE:** Wajib mencantumkan sumber referensi data pada bagian `Data Loading`.

3. Sebelum menentukan tabel, kolom, atau hal lain dalam dataset mana yang akan dijadikan analisis dan visualisasi data, lakukan identifikasi dan penjabaran masalah supaya dapat memudahkan kamu dalam melakukan analisis. Kamu bisa menggunakan metode apapun seperti analisis SWOT, Fish bone diagram, 5W+1H, dsb.
  - **Contoh:**
  - Problem Statement: `Mengetahui Preferensi dan Perilaku Konsumsi Makanan di Area Urban di Indonesia dalam kurun waktu tahun 2021`

  - Penjabaran masalah dengan metode 5W+1H:

    - Kota mana dengan rata-rata % pengeluaran makan paling besar?
    - Bagaimana perilaku pemilihan makanan berdasarkan harga terhadap social class masyarakat?
    - Apakah tingkat pendidikan sarjana memiliki preferensi memilih makanan-makanan yang sehat?
    - Apakah warga DKI Jakarta masih mengonsumsi makanan tradisional?
    - Usia berapa saja yang masih mengonsumsi makanan tradisional?
    - dsb.
  - Pertanyaan-pertanyaan/penjabaran masalah di atas dapat dijawab dengan data visualisasi dan analisis statistik.

4. Setelah melakukan identifikasi dan penjabaran masalah, tentukan metrik/data apa saja yang diperlukan lalu tarik data yang diperlukan dari dataset yang sudah ditentukan menggunakan SQL. `Cantumkan semua query yang dibuat untuk menarik semua data yang diperlukan dalam milestone ini`.
5. **Perlu diperhatikan** bahwa penjabaran masalah untuk dijawab menggunakan data visualisasi dan analisis statistik **HARUS** mengikuti kriteria berikut:
  - Minimal terdapat `6 penjabaran` masalah dimana 4 penjabaran untuk `visualisasi data`, 1 penjabaran untuk `statistik deskriptif`, dan 1 penjabaran untuk `statistik inferensial`.
6. Untuk `Data Visualisasi` dibebaskan menggunakan tipe visualisasi (batang, garis, dsb) dan library (matplotlib, pyplot, seaborn, dsb) apapun, disesuaikan dengan penjabaran masalahnya. `Minimal 4 visualisasi sesuai dengan jumlah minimum penjabaran untuk bagian visualisasi data`. **WAJIB** memberikan insight di tiap visualisasi data.
7. Untuk `Statistik Deskriptif`, pilih minimal salah satu perhitungan/analisis statistik deskriptif seperti *central tendency*, *measure of variance*, *outlier analysis*, *distribution*, dsb. `Sesuaikan dengan penjabaran masalah yang ditentukan`.
8. Untuk `Statistik Inferensial`, pilih minimal salah satu perhitungan/analisis statistik inferensial seperti *confidence interval*, *statistical significance*, *statistical testing*, *hypothesis testing: one sample, two sample independent, paired test, ANOVA, chi-square*, dsb. `Sesuaikan dengan penjabaran masalah yang ditentukan`.
9. Output dari milestone ini adalah dashboard data visualisasi menggunakan `Tableau Public` dan analisis serta pengolahan data di `jupyter notebook`.

## Notebook Instructions
1. Lakukan data cleaning dan preprocessing pada notebook
2. Notebook harus mengikuti format berikut:
  1. Perkenalan
      > Bab pengenalan harus diisi dengan identitas.

  2. Identifikasi Masalah
      > Bab ini harus menyantumkan **topik permasalahan**, **problem statement**, **latar belakang**, serta **penjabaran masalah** yang ingin dianalisis menggunakan metode statistik dan data Visualisasi.

  3. Data Loading 
      > Bagian ini berisi proses *data loading* dan eksplorasi data sederhana. Cantumkan query SQL masing-masing data yang di-load jika menggunakan dari BigQuery atau server SQL lainnya. Tampilkan pulai datanya.

  4. Data Cleaning
      > Bagian ini berisi proses penyiapan data berupa data cleaning sebelum dilakukan *explorasi data* lebih lanjut. Proses cleaning dapat berupa memberi nama baru untuk setiap kolom, mengisi missing values, menghapus kolom yang tidak dipakai, dan lain sebagainya.

  5. Analisis dan perhitungan
      > Bagian ini berisi proses analisis, penjelasan, perhitungan statistik deskriptif, inferensial, serta pembuatan visualisasi data. Untuk visualisasi data wajib memberikan insight di tiap visualisasinya.

  6. Pengambilan Kesimpulan
      > Pada bab terakhir ini, **harus berisi** kesimpulan yang mencerminkan solusi/rekomendasi/jawaban atas permasalahan yang diangkat serta menarik benang merah dari seluruh analisis dan perhitungan secara singkat, jelas, dan padat.

3. Simpan notebook dengan judul h8dsft_Milestone1_<nama-student>.ipynb, misal h8dsft_Milestone1_raka_ardhi.ipynb

## Dashboard Instructions

1. Dashboard dibuat menggunakan `Tableau`.
2. Dashboard yang dibuat terdiri dari 2 bagian : `Visualisasi` dan `Statistical Analysis` yang dapat dibuat dalam 1 halaman atau multi halaman.
3. Untuk bagian Visualisasi :
  - Minimal ada 4 figure/visualisasi data yang ditampilkan dalam halaman `Visualisasi` yang sesuai dengan yang dibuat pada Notebook.
  - Minimal ada 1 interactivity pada dashboard
  - Tidak perlu menulis insightnya, dashboard visualisasi sejatinya hanya kumpulan visualisasi data
  - Apabila jenis plot pada dashboard dengan di Python berbeda, dari segi jenis dan hasil, tidak masalah jika lampirkan plot dari dashboard ke notebook dan tetap tampilkan data yang sudah dipreprocess pada notebook.
4. Untuk bagian Statistical Analysis:
  - Tulis proses analisis statistik deskriptif dan inferential yang dilakukan di notebook dari masalah yang diangkat hingga kesimpulan dari hasil analisis statistik.

5. Presentasikan dashboard yang telah dibuat pada P1W1D4PM.

---

# Assignment Submission

1. Tambahkan URL dashboard di bagian paling atas `.ipynb` dan di README.
2. Tidak adanya URL dashboard di file .ipynb akan menyebabkan tidak dinilainya deployment Streamlit.
3. Push Assigment yang telah dibuat ke akun Github masing-masing student dan Github Classroom.

---

## Assignment Rubrics

<img src="https://github.com/fahmimnalfrzki/Dataset/raw/main/Screenshot%202022-12-16%20at%2016.28.37.png"></img>

---

## Score Reduction

Jika Student terlambat mengumpulkan dengan waktu yang ditentukan, maka Graded Challenge akan diberi poin nol.

---

```
Total Points : 60

Catatan : Penilaian Milestone  juga dapat dipengaruhi oleh aktivitas student selama Phase 0 berlangsung, baik sesi kelas maupun sesi mentoring dengan buddy-nya masing-masing sehingga terdapat kemungkinan adanya penambahan atau pengurangan nilai diluar rubric yang telah disebutkan diatas.
```
