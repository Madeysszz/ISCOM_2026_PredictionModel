# Hands-On Supervised Machine Learning — Regression

Praktikum regresi untuk pemula dengan Python 3.10+. Dataset 500 rumah bersifat sintetis dan tidak mewakili harga pasar aktual.

## Penggunaan

Jalankan perintah berikut dari folder proyek:

```bash
pip install -r requirements.txt
python 00_generate_dataset.py
jupyter notebook
```

Buka `supervised_learning_regression.ipynb` dari folder proyek dan jalankan sel dari atas ke bawah. Semua output sudah tersimpan di notebook.

## Isi

Notebook tunggal mencakup konsep dasar, eksplorasi data, training dan prediksi, evaluasi tiga model, serta tuning Decision Tree dengan validation dan cross-validation.

## Hasil eksekusi

Pada test set 20%, Linear Regression memperoleh MAE 33,035 juta rupiah, RMSE 40,507 juta rupiah, dan R² 0,983. Angka dihitung dari eksekusi notebook 04, bukan nilai asumsi.
