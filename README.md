## Aplikasi Regresi untuk Pemecahan Problem

### Deskripsi Singkat:
Proyek ini bertujuan untuk menganalisis korelasi antara jumlah kertas soal latihan yang dikerjakan oleh siswa dengan indeks kinerja mereka. Regresi linear sederhana, regresi model pangkat, dan regresi model linearisasi laju pertumbuhan jenuh digunakan untuk memodelkan hubungan antara variabel latihan soal yang dikerjakan dan indeks kinerja.

### Data:
Data yang digunakan dalam proyek ini disimpan dalam file CSV dengan nama 'Student_Performance.csv'. Data ini berisi kolom 'Sample Question Papers Practiced' yang menunjukkan jumlah kertas soal latihan yang dikerjakan oleh siswa dan kolom 'Performance Index' yang menyimpan indeks kinerja mereka.

### Libraries yang Digunakan:
- **Pandas**: Digunakan untuk manipulasi dan analisis data.
- **NumPy**: Untuk operasi numerik pada data.
- **Matplotlib**: Digunakan untuk visualisasi data dan plot.
- **SciPy**: Untuk melakukan optimisasi kurva dalam regresi model laju pertumbuhan jenuh.

### Metode Regresi yang Diterapkan:
1. **Regresi Linear Sederhana**:
   - Digunakan untuk memodelkan hubungan linear antara variabel latihan dan indeks kinerja.
   - Menggunakan formula regresi linear sederhana untuk menghitung koefisien kemiringan (b1) dan intersep (b0).

2. **Regresi Model Pangkat**:
   - Regresi model pangkat digunakan ketika hubungan antara variabel independen (jumlah kertas soal) dan variabel dependen (indeks kinerja) tidak linear secara linier.
   - Dalam implementasi ini, regresi model pangkat dilakukan dengan mengubah kedua variabel menjadi logaritmik, sehingga membentuk model linear yang dapat dihitung dengan regresi linear sederhana.

3. **Regresi Model Linearisasi Laju Pertumbuhan Jenuh**:
   - Regresi model linearisasi laju pertumbuhan jenuh digunakan untuk kasus di mana pertumbuhan tidak terbatas tetapi mencapai tingkat jenuh seiring bertambahnya variabel independen.
   - Dalam proyek ini, regresi ini diimplementasikan menggunakan fungsi kurva khusus yang disesuaikan dengan model laju pertumbuhan jenuh.

### Evaluasi Model:
- Root Mean Square Error (RMS) digunakan sebagai metrik evaluasi untuk mengevaluasi seberapa baik model memfitting data.
- RMS mengukur deviasi antara nilai prediksi dan nilai observasi dalam satuan yang sama dengan variabel target.

### Output:
- Plot hasil regresi untuk ketiga metode yang diimplementasikan.
- Koefisien regresi dan fungsi regresi untuk masing-masing model.
- RMS untuk masing-masing model, yang menunjukkan seberapa baik model memfitting data.

### Kesimpulan:
Proyek ini memberikan pemahaman tentang hubungan antara jumlah kertas soal latihan yang dikerjakan oleh siswa dengan indeks kinerja mereka. Melalui berbagai metode regresi, proyek ini memberikan pandangan yang komprehensif tentang model yang paling cocok untuk data tersebut, serta seberapa baik model-model tersebut memprediksi kinerja siswa.
