###### Submission 1: Mendeteksi nasabah bank yang berpotensi untuk beralih / berhenti (churn)
***
Nama: **Antonius Blantran de Rozari**
Username dicoding: **derozari**

|         | Deskripsi |
| ------- | --------- |
| Dataset | [Banking Customer Churn](https://www.kaggle.com/datasets/barelydedicated/bank-customer-churn-modeling)    |
| Masalah  | Bagaimana mendeteksi nasabah bank yang berpotensi berhenti / pindah (churn) |
| Solusi Machine Learning     | Semua fitur yang dari nasabah, diumpankan ke input ANN (Artificial Neural Network). Output dari ANN ini akan mengindikasikan apakah nasabah yang bersangkutan berpotensi untuk pindah / berhenti           |
| Metode Pengolahan     |  Data awal dalam format CSV. Beberapa kolom seperti Nama atau Customer ID dibuang dan tidak digunakan. Fitur numerik dipetakan ke interval \[0,1\] sementara fitur kategorikal dipetakan menjadi bilangan bulat positif yang sesuai dengan nilai unik fitur tersebut        |
| Arsitektur Model      |    Multi Layer Perceptron       |
| Metrik evaluasi      |    memaksimalkan nilai akurasi dataset evaluasi      |
| Performa model      |     val_binary_accuracy = 0.83      |


