# Machine Learning (ITA0606)

This repository contains coursework, lab programs, assignments, and the capstone project for **Machine Learning (Course Code: ITA0606)** by Kiran Thammisetty.

---

## 📂 Repository Contents

### 1. 🛡️ Capstone Project: [Fake Job Posting Detection System](./Fake%20Job%20Posting%20Detection/)
An end-to-end Machine Learning web application and cyber-defense platform designed to detect fraudulent recruitment listings and employment scams in real time.
- **Models**: Dual Consensus Architecture using **Logistic Regression** and **Support Vector Machine (LinearSVC)** with Platt scaling.
- **Dataset**: EMSCAD benchmark dataset (5,000 real and fraudulent postings).
- **Features**: 1,617 engineered dimensions (TF-IDF NLP representations + tabular metadata heuristics).
- **Accuracy**: 100% on held-out test split (N=1,000) with 0 False Positives and 0 False Negatives.
- **Web App**: Full-stack application built with FastAPI, Jinja2, responsive modern CSS (desktop + mobile support), and multimodal input options (Form, Photo/Camera OCR scan, URL scanner, Raw Text).
- **Quick Start**:
  `ash
  cd "Fake Job Posting Detection"
  pip install -r requirements.txt
  python run_server.py
  `
  Then open `http://127.0.0.1:8000` in your browser.

---

### 2. 📝 Course Assignments
Comprehensive 25-page course assignments covering machine learning algorithms, mathematical derivations, and practical implementations:
- [Assignment 1 (25 Pages)](./ITA06_Machine_Learning_Assignment_1_25_Pages.docx)
- [Assignment 2 - CO2 (25 Pages)](./ITA06_Machine_Learning_Assignment_2_CO2_25_Pages.docx)
- [Assignment 3 - CO3 (25 Pages)](./ITA06_Machine_Learning_Assignment_3_CO3_25_Pages.docx)
- [Assignment 4 - CO4 (25 Pages)](./ITA06_Machine_Learning_Assignment_4_CO4_25_Pages.docx)
- [Assignment 5 - CO5 (25 Pages)](./ITA06_Machine_Learning_Assignment_5_CO5_25_Pages.docx)
- [Google Colab Assignments Notebook](./Assignments)

---

### 3. 🧪 Lab Programs
- [Google Colab Lab Programs Notebook](./Lab%20programs)
