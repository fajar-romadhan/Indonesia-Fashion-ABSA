# ABSA-FMI (Aspect-Based Sentiment Analysis Fashion Marketplace Indonesia)

[![Live Web Application](https://img.shields.io/badge/Demo-Live_Web_App-blue?style=for-the-badge&logo=vercel)](https://absa-lstm-project.vercel.app/)
[![Intellectual Property](https://img.shields.io/badge/HKI-Kemenkumham_RI-green?style=for-the-badge)](https://e-hakcipta.dgip.go.id/)
[![Research](https://img.shields.io/badge/IEEE-9th_ICVEE_2026-orange?style=for-the-badge)](https://icvee.unesa.ac.id/)

Sistem analisis sentimen berbasis aspek (**Aspect-Based Sentiment Analysis / ABSA**) untuk ulasan produk fashion pada marketplace e-commerce di Indonesia menggunakan arsitektur deep learning **Multi-Output Long Short-Term Memory (LSTM)** dengan mekanisme **Attention** dan representasi fitur kata **Word2Vec**.

Sistem ini mengevaluasi opini konsumen secara simultan ke dalam **6 aspek produk utama**:
1. **Kualitas** (Quality)
2. **Bahan** (Material)
3. **Ukuran** (Size / Fit)
4. **Desain** (Design)
5. **Warna** (Color)
6. **Kenyamanan** (Comfort)

Setiap aspek diprediksi ke dalam 3 polaritas sentimen: **Positif**, **Negatif**, atau **Netral**.

---

## 📖 Dokumentasi & Manual Book

Petunjuk lengkap penggunaan aplikasi web, Chrome extension, pipeline preprocessing data, representasi kata, hingga arsitektur model dan evaluasi performa model (Confusion Matrix & AUC-ROC) telah disusun dalam dokumen resmi:

- 📄 **[Manual Book Sistem ABSA-FMI.pdf](Manual%20Book%20Sistem%20ABSA-FMI.pdf)** *(Panduan Penggunaan dan Dokumentasi Teknis Sistem)*

---

## ⚖️ Hak Kekayaan Intelektual (HKI)

Buku panduan dan sistem ini telah terdaftar dan dilindungi secara hukum oleh **Direktorat Jenderal Kekayaan Intelektual (DJKI), Kementerian Hukum dan HAM Republik Indonesia**:

- **Jenis Ciptaan**: Karya Tulis (Buku Panduan / Petunjuk Penggunaan Sistem)
- **Judul Ciptaan**: *Manual Book Sistem ABSA-FMI (Aspect-Based Sentiment Analysis Fashion Marketplace Indonesia)*
- **Nomor Pencatatan**: `001433941`
- **Nomor Permohonan**: `EC002026151383`
- **Tanggal Permohonan / Terbit**: 21 Agustus 2026
- **Pencipta**: Fajar Romadhan, Dr. Ari Muzakir, Dr. Usman Ependi
- **Pemegang Hak Cipta**: Fajar Romadhan

---

## 🔬 Publikasi Ilmiah Terkait

Penelitian dan arsitektur model deep learning sistem ini dipresentasikan pada konferensi internasional:
> **Fajar Romadhan, Ari Muzakir, Usman Ependi, Andri**  
> *"Attention-Enhanced Multi-Output LSTM for Multi-Aspect Sentiment Understanding in Indonesian Fashion Marketplace"*  
> **The 9th IEEE International Conference on Vocational Education and Electrical Engineering (ICVEE 2026)**, 17 September 2026 (First Author & Lead Presenter).

---

## 🌐 Live Demo & Aplikasi
- **Aplikasi Web**: [https://absa-lstm-project.vercel.app/](https://absa-lstm-project.vercel.app/)
