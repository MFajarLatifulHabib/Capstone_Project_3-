# E-Commerce Customer Analysis

**Author:** Muhamad Fajar Latiful Habib

## Business Problem

Di era modern ini, mempertahankan pelanggan menjadi kunci utama bagi bisnis agar tetap kompetitif. Menurut penelitian dari Harvard Business Review, meningkatkan retensi pelanggan sebesar 5% dapat meningkatkan keuntungan hingga 25-95%. Pelanggan setia juga cenderung membelanjakan lebih banyak uang, dengan peningkatan pengeluaran sebesar 67% pada bulan 31-36 dibandingkan dengan bulan 0-6, seperti dilaporkan oleh Accenture. Selain itu, biaya untuk mendapatkan pelanggan baru bisa mencapai lima kali lebih tinggi daripada mempertahankan pelanggan yang sudah ada, menurut Invesp.

Temuan-temuan ini menunjukkan pentingnya menjaga hubungan baik dengan pelanggan yang sudah ada, termasuk dalam bisnis E-commerce. Misalnya, laporan dari McKinsey & Company mengungkapkan bahwa peningkatan pengalaman pelanggan dapat meningkatkan loyalitas dan retensi. Lebih jauh lagi, ketika pelanggan setia meninggalkan bisnis, biaya untuk mendapatkan pelanggan baru dan mencapai tingkat loyalitas yang sama bisa mencapai 16 kali lebih besar.

Oleh karena itu, perusahaan E-commerce ingin menganalisis pelanggan yang berhenti menggunakan layanan mereka, yang dikenal sebagai customer churn. Dengan mengetahui dan memprediksi pelanggan yang berpotensi churn, perusahaan dapat menyesuaikan strategi pemasaran mereka serta memberikan penawaran khusus untuk menjaga pelanggan tetap setia.

## Pernyataan Masalah

Mengabaikan pelanggan setia yang churn dapat merugikan perusahaan. Untuk mencegah hal ini, perusahaan harus berusaha menjaga keterlibatan pelanggan di platform e-commerce. Salah satu pendekatan yang bisa digunakan adalah memberikan promosi. Namun, tanpa strategi yang baik, pengeluaran untuk promosi dan sumber daya yang digunakan bisa menjadi tidak efisien.

## Tujuan

Untuk menghadapi masalah tersebut, perusahaan bisa melakukan prediksi customer churn sebagai langkah preventif. Dengan mengetahui pelanggan yang berpotensi churn, perusahaan dapat menyusun strategi pemasaran yang lebih terarah, yang pada gilirannya dapat mengurangi biaya pemasaran dan meningkatkan profitabilitas dengan mempertahankan pelanggan setia.

Selain itu, mengetahui faktor-faktor yang mempengaruhi customer churn juga membantu dalam membuat keputusan strategis yang lebih baik dalam pemasaran.

## Pendekatan Analitik

Pendekatan analitik yang digunakan melibatkan membangun model, pengujian, dan penerapan model machine learning klasifikasi untuk memprediksi apakah pelanggan akan mengalami churn atau tidak berdasarkan data historis mereka.

## Metode Evaluasi

Untuk mengevaluasi kinerja model, digunakan metrik berikut:

| **N-Pred** | **P-Pred** |
|------------|------------|
| **N-Act**  | TP         | FP         |
| **P-Act**  | FN         | TP         |

- **Target:**
  - `0`: Pelanggan tidak churn
  - `1`: Pelanggan churn

- **Type 1 Error (False Positive):** Mengeluarkan biaya untuk pelanggan yang kurang tepat atau pelanggan yang tidak akan churn.

- **Type 2 Error (False Negative):** Hilangnya pelanggan loyal.

Berdasarkan dampaknya, pemilihan model yang tepat harus fokus pada mengurangi kehilangan pelanggan loyal sambil meminimalkan biaya pemasaran untuk pelanggan yang kurang relevan. Untuk menyeimbangkan recall dan precision pada pelanggan churn, metrik yang digunakan adalah ROC-AUC.

## Struktur Data

1. **Data Understanding**
2. **Data Cleaning**
3. **Data Analysis**
4. **Data Preprocessing and Feature Engineering**
5. **Modeling**
6. **Conclusion and Recommendation**

