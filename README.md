# 📄ATS_useing_SentenceTransformer

This project compares the content of a candidate's resume PDF with a job description using NLP. It uses the `SentenceTransformer` model to calculate cosine similarity and visualizes the match score with a gauge-style chart.

## 🚀 Overview

This tool automates resume screening by calculating how well a resume aligns with a job description. It’s particularly useful for recruiters and HR professionals looking for a quick, visual evaluation of candidate-job fitment.

## ✨ Features

- Extracts text from PDF resumes using `PyMuPDF`
- Computes similarity score with job descriptions using `Sentence Transformers`
- Uses `cosine similarity` for comparison
- Visualizes the result with an intuitive gauge using `matplotlib`

## 🛠 Installation

Make sure you have Python 3.7 or above installed. Then, install the required libraries:

```bash
pip install matplotlib sentence-transformers PyMuPDF scikit-learn
```
