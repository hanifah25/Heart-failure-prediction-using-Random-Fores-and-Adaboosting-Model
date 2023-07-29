# Heart-failure-prediction-using-Random-Fores-and-Adaboosting-Model

## Objective
prediksi gagal jantung untuk meningkatkan kualitas hidup pasien dengan memungkinkan diagnosis dini dan pengobatan yang lebih efektif.

## Problem Statement
Gagal jantung adalah kondisi medis yang disebabkan oleh berbagai faktor seperti hipertensi, penyakit jantung koroner, atau kerusakan jantung lainnya. Tujuan dari prediksi gagal jantung dalam konteks machine learning adalah untuk mengembangkan model yang dapat memprediksi risiko seseorang terkena gagal jantung berdasarkan faktor-faktor risiko tertentu seperti usia, jenis kelamin, tekanan darah, kadar gula darah, kadar kolesterol, dan riwayat medis.

## Result
best model: ada
cross-val mean: 0.9382716049382716
Cross validation Metrik yang digunakan untuk evaluasi adalah recall, dan skema cross-validation yang digunakan adalah Stratified K-Fold. Pada setiap iterasi, code akan menghitung nilai recall pada data train yang dipartisi menggunakan skema Stratified K-Fold. Setelah selesai melakukan cross validation pada masing-masing model, code akan menampilkan nilai recall rata-rata dan standar deviasi pada setiap fold, serta menampilkan rentang nilai recall yang dihasilkan pada setiap model.juga membandingkan nilai recall rata-rata dari semua model dan memilih model yang memiliki nilai recall rata-rata tertinggi sebagai model terbaik. dari data di atas dapat kita lihat best model dari hasil prediksi adalah ada dengan nilai cross-val mean: 0.93

## Field column
<img width="817" alt="field column - heart failure" src="https://github.com/hanifah25/Heart-failure-prediction-using-Random-Fores-and-Adaboosting-Model/assets/52957685/0187127d-e676-4e1e-8620-97914a4e812d">
