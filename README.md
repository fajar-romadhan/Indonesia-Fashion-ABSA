# ABSA-FMI: Aspect-Based Sentiment Analysis for Indonesian Fashion Marketplace

Official repository and documentation for **Sistem ABSA-FMI (Aspect-Based Sentiment Analysis Fashion Marketplace Indonesia)**, utilizing Multi-Output Long Short-Term Memory (LSTM) with Attention Mechanism and Word2Vec word representation.

---

## Overview

This project provides an automated pipeline for aspect-based sentiment classification of Indonesian e-commerce consumer reviews from fashion marketplace listings. The system evaluates review text across six primary product aspects simultaneously:

1. **Quality (Kualitas)**
2. **Material (Bahan)**
3. **Size / Fit (Ukuran)**
4. **Design (Desain)**
5. **Color (Warna)**
6. **Comfort (Kenyamanan)**

Each aspect is classified into three polarity classes: **Positive**, **Negative**, or **Neutral**.

---

## Repository Structure

| File | Description |
|---|---|
| `Annotator Agreement.csv` | Inter-annotator reliability and agreement metrics during manual labeling. |
| `Fashion Review Dataset.xlsx` | Processed and aspect-labeled review dataset for model training and evaluation. |
| `Raw Review Dataset.xlsx` | Unprocessed raw review corpus scraped from fashion product listings. |
| `Manual Annotation.csv` | Ground-truth manual labeling sample records. |
| `Indonesia_Fashion_ABSA_Labeling.ipynb` | Jupyter notebook for data preprocessing, text cleaning, and aspect labeling pipeline. |
| `Indonesia_Fashion_ABSA_Prediction.ipynb` | Jupyter notebook implementing the multi-output LSTM architecture, training, and evaluation. |
| `Manual Book Sistem ABSA-FMI.pdf` | Complete technical reference and operational user guide for the ABSA-FMI system. |

---

## Documentation

The complete technical reference and operational guide is available in this repository:

- **Technical Manual & User Guide**: [Manual Book Sistem ABSA-FMI.pdf](Manual%20Book%20Sistem%20ABSA-FMI.pdf)  
  *Contains comprehensive documentation on data collection via Chrome Extension, web application interface, preprocessing pipeline, Word2Vec embedding, neural network architecture, and evaluation metrics (Confusion Matrix and AUC-ROC).*

---

## Intellectual Property Rights

The ABSA-FMI system and its accompanying documentation are officially registered under the Directorate General of Intellectual Property (DJKI), Ministry of Law and Human Rights of the Republic of Indonesia (Kemenkumham RI):

- **Type of Work**: Written Work (System Manual & User Guide)
- **Title**: *Manual Book Sistem ABSA-FMI (Aspect-Based Sentiment Analysis Fashion Marketplace Indonesia)*
- **Registration Number**: 001433941
- **Application Number**: EC002026151383
- **Registration Date**: August 21, 2026
- **Authors**: Fajar Romadhan, Dr. Ari Muzakir, Dr. Usman Ependi
- **Copyright Holder**: Fajar Romadhan

---

## Associated Publication

The underlying research methodology and deep learning model architecture were presented at:

> **Fajar Romadhan, Ari Muzakir, Usman Ependi, Andri**  
> *"Attention-Enhanced Multi-Output LSTM for Multi-Aspect Sentiment Understanding in Indonesian Fashion Marketplace"*  
> **The 9th IEEE International Conference on Vocational Education and Electrical Engineering (ICVEE 2026)**  
> Presented on September 17, 2026. Paper ID: 1571298976.  
> *IEEE Xplore proceedings publication in progress.*

---

## Live Demonstration

- **Web Application**: [https://absa-lstm-project.vercel.app/](https://absa-lstm-project.vercel.app/)

---

## Authors & Affiliation

- **Fajar Romadhan, S.Kom** — Department of Information Systems, Universitas Bina Darma, Palembang, Indonesia
- **Dr. Ari Muzakir, S.Kom., M.Cs** — Universitas Bina Darma, Palembang, Indonesia
- **Dr. Usman Ependi, S.Kom., M.Kom** — Universitas Bina Darma, Palembang, Indonesia
