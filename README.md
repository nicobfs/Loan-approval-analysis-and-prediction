![dataset-cover](https://user-images.githubusercontent.com/55326839/192535286-e4699482-2115-4249-b77e-580b2b525325.jpeg)

## **Should This Loan be Approved or Denied Prediction 💸**

---
## **Background**
[Dataset](https://www.kaggle.com/datasets/mirbektoktogaraev/should-this-loan-be-approved-or-denied) yang kami gunakan adalah dataset dari U.S. Small Business Administration (SBA). SBA merupakan pihak ketiga yang berperan membantu pihak pengusaha kecil di pasar kredit AS melalui program pemberian jaminan yang dirancang agar pihak Bank dapat memberikan pinjaman kepada pengusaha kecil. SBA bertindak seperti penyedia asuransi untuk mengurangi risiko pihak Bank dengan menutupi beberapa kerugian melalui jaminan yang diberikan jika para pengusaha kecil gagal bayar.

## **Role**
Data Science Team dari perusahaan layanan konsultasi data analytic and decisioning (DAD) yang bermitra dengan SBA

## **Goals**
Menurunkan nasabah yang gagal bayar

## **Business Metrics**
Business Matrics yang kami gunakan sebagai pengukur keberhasilan dari goals yang ingin kami capai adalah Default Rate (rasio gagal bayar dari total pinjaman yang diterima).

## **Objective**
Membuat model machine learning untuk melakukan profiling atau memprediksi profile nasabah yang berpotensi gagal bayar sehingga perusahaan mampu melakukan assestment nasabah lebih akurat dan meningkatkan performa kerja perusahaan


## **Methods**
Project ini membutuhkan numpy, pandas, matplotlib, seaborn, sklearn, imblearn, xgboost. Jadi, Anda mungkin perlu menginstal ini jika ingin mengujinya.

Proses yang kami lakukan secara garis besar adalah:

1. EDA
Descriptive Statistics
Univariate Analysis
Multivariate Analysis

2. Preprocessing
Data Cleansing
Feature Encoding
Feature Engineering
Feature transformation: BoxCox Standarization


3. Modeling
Kami mencoba 4 jenis model classification untuk melihat mana yang paling baik dalam memprediksi targer yaitu:

Decission Tree
Random Forest
Logistics Regression
XGBoost
Adaboost
GradientBoost

## **Result**
![Teks Alternatif](https://github.com/nicobfs/Loan-approval-analysis-and-prediction/blob/main/result.png)
