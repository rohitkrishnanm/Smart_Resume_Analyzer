# 📄 Smart Resume Analyzer – AI-Powered Resume Screening Tool

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-FF4B4B.svg)](https://streamlit.io/)
[![Model](https://img.shields.io/badge/NLP%20Backbone-SentenceTransformers-blue.svg)](https://www.sbert.net/)
[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org)

> A powerful AI-based resume analyzer that uses **semantic similarity, NLP parsing, skill extraction, and PDF reading** to match resumes with job descriptions — all through an easy-to-use Streamlit web interface.

---

## 🚀 Project Overview

This application evaluates resumes against job descriptions using both **keyword relevance** and **semantic embeddings**. It supports bulk PDF uploads and generates a **PDF ranking report**, making it ideal for:

- Recruiters & HR professionals
- AI-based hiring systems
- Students preparing for job matching
- Resume screening automation tools

---

## 🧠 Features

✔️ Upload **multiple resumes in PDF** format  
✔️ Enter a custom **job description**  
✔️ Extract **skills**, **projects**, and **experience** sections  
✔️ Analyze for **relevance** (semantic + keyword match)  
✔️ Generate and **download a PDF ranking report**  
✔️ Powered by **Sentence Transformers**, **SpaCy NLP**, and **RapidFuzz**  
✔️ Fully built with **Streamlit** for easy UI interaction

---

## 💻 Live Demo (Optional)

> 🔗 Coming soon – hosted on Streamlit Cloud or Hugging Face Spaces  
Or run locally as shown below 👇

---

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/ai-resume-analyzer.git
cd ai-resume-analyzer
pip install -r requirements.txt
---

🧪 How to Use
▶️ Run the app locally
bash
Copy
Edit
streamlit run app.py
Paste a job description in the textbox

Upload one or more resume PDFs

Click Analyze Resumes

View results in the browser and download the PDF ranking report
