--Deskripsi Project
Program ini bertujuan untuk mengklasifikasi tingkat stres mahaiswa berdasarkan aktivitas harian dengan algoritma K-Nearest Neightbbors (KNN).
Kolom yang digunakan seperti durasi tidur, waktu belajar, waktu layar, asupan kafein, aktivitas fisik, kualitas tidur untuk menganalisis tingkat stres mahasiswa.

--Syarat
1.Pyhton 3.8 atau lebih baru
2.Modul yang digunakan pandas, scikit-learn, matplotlib, seaborn

--Struktur Data
1.Student_ID: ID unik untuk setiap siswa.
2.leep_Duration: Durasi tidur siswa (dalam jam).
3.Study_Hours: Waktu belajar (dalam jam).
4.Screen_Time: Waktu layar (dalam jam).
5.Caffeine_Intake: Asupan kafein (mg per hari).
6.Physical_Activity: Aktivitas fisik (dalam jam).
7.Sleep_Quality: Kualitas tidur siswa (skala 1-10).

--Instalasi
1.Siapkan 1 folder
1.download/run file B4_AVD.ipynb dan masukkan ke folder
2.download sleep_student_pattern.csv dan masukkan ke folder yang sama

--Penjelasan singkat program
1.physical_activity dikonversi ke jam
2.Kategori tingkat stress dibagi 3 yaitu low, medium, high
3.K=5
4.Dataset dibagi menjadi 80% data training dan 20% data testing dengan metode random
5.Menilai performa dengan akurasi, presisi, recall
6.Visualisasi adda 3 yaitu scatter plot, bar plot, dan pie chart
