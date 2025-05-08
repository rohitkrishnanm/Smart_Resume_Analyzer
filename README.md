Based on your project (`app.py` + `resume_analyzer.py`), here is a professional and attractive `README.md` file for your **AI Resume Analyzer using Sentence Transformers**, suitable for GitHub upload.

---

````markdown
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
````

Make sure to also install **spaCy** models and required fonts if using `fpdf`.

```bash
python -m spacy download en_core_web_sm
```

---

## 📂 Project Structure

```
ai-resume-analyzer/
├── app.py                   # Streamlit UI
├── resume_analyzer.py       # Core logic for parsing, analysis & scoring
├── utils.py                 # NLP and model loader helpers (not uploaded yet)
├── requirements.txt
├── README.md
└── assets/                  # Optional: Logos, PDFs, etc.
```

---

## 🧪 How to Use

### ▶️ Run the app locally

```bash
streamlit run app.py
```

1. Paste a job description in the textbox
2. Upload one or more resume PDFs
3. Click **Analyze Resumes**
4. View results in the browser and download the PDF ranking report

---

## 🎯 Scoring Criteria

| Factor                     | Weight                              |
| -------------------------- | ----------------------------------- |
| ✅ Primary Skill Match      | High                                |
| 🔄 Secondary Skill Match   | Medium                              |
| 📆 Total Experience        | Medium                              |
| 🔍 Relevance of Experience | High                                |
| 🧪 Project Skill Relevance | Medium                              |
| 📊 Final Score             | Weighted composite of above factors |

Semantic similarity is computed using **Sentence Transformers**, while keyword extraction uses **spaCy** and fuzzy matching with **RapidFuzz**.

---

## 📄 Sample Output

* PDF report with ranked resumes
* Shows job title relevance, matched skills, experience duration, and final score

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE)

---

## 👨‍💻 Author

**Rohit Krishnan**
Business and Technology Strategist
🌐 [rohitkrishnan.co.in](https://rohitkrishnan.co.in)
📧 [rohitkrishnanm@gmail.com](mailto:rohitkrishnanm@gmail.com)
💼 [LinkedIn](https://linkedin.com/in/rohit-krishnan-320a5375)

---

> ⭐ Star this repo if it helped you, and feel free to fork, contribute, or share with your hiring/placement network!

````

---

### ✅ Next Steps:

1. Place this as your new `README.md` file in the project folder.
2. Ensure `utils.py` is added if it's missing (as referenced in `resume_analyzer.py`).
3. Commit and push to GitHub:
```bash
git add .
git commit -m "Initial commit: AI Resume Analyzer with README"
git push origin main
````

Would you like me to create a `LICENSE` and `.gitignore` file as well?
