## uts pengolahan citra digital menggunakan algoritma svm

 SVM (Support Vector Machine)

**SVM (Support Vector Machine)** adalah salah satu algoritma *Supervised Learning* yang paling populer, digunakan untuk masalah **klasifikasi** (paling umum) dan **regresi**.

### Konsep Utama

1.  **Tujuan:** Tujuan utama SVM adalah menemukan **Hyperplane** (bidang pemisah) terbaik yang dapat memisahkan kelas-kelas data dalam ruang berdimensi tinggi. 

2.  **Hyperplane Terbaik:** Hyperplane terbaik adalah bidang yang memiliki **Margin** (jarak) maksimum terhadap titik-titik data terdekat dari setiap kelas.

3.  **Support Vectors:** Titik-titik data yang paling dekat dengan *Hyperplane* dan berkontribusi langsung pada penentuan posisi dan orientasi *Hyperplane* disebut **Support Vectors**. Hanya *Support Vectors* ini yang penting; titik data lain diabaikan, membuat SVM sangat efisien.

###  Kegunaan Utama

* **Klasifikasi Linier:** Jika data dapat dipisahkan secara sempurna oleh garis lurus atau bidang datar.
* **Klasifikasi Non-Linier:** Jika data tidak dapat dipisahkan secara linier, SVM menggunakan teknik yang disebut **Fungsi Kernel (*Kernel Trick*)** untuk memetakan data ke ruang dimensi yang lebih tinggi di mana pemisahan linier menjadi mungkin. Kernel yang umum digunakan meliputi:
    * *Polynomial Kernel*
    * *Radial Basis Function* (RBF) Kernel (paling sering digunakan)
    * *Sigmoid Kernel*

https://drive.google.com/drive/folders/19puVtrTm4oPGx4W3ium1Sgzf13Oivd9F?usp=drive_link

| No | Keterangan | Gambar |
|----|-------------|--------|
| 1  | Grafik Akurasi | ![Akurasi](https://drive.google.com/uc?export=view&id=1AbCdEfGhIjKlMnO) |
| 2  | Contoh Daun | ![Daun](images/daun_herbal.jpg) |