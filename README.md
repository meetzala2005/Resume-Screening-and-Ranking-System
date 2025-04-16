# 🧠 AI-powered Resume Screening and Ranking System

An intelligent web application built with **Python** and **Streamlit** that automatically screens, parses, and ranks resumes based on their similarity to a given job description using **NLP** and **cosine similarity**.

---

## 🚀 Features

- 📄 Upload multiple **PDF resumes**
- 📋 Paste any **Job Description**
- 🧠 Uses **TF-IDF vectorization** + **Cosine Similarity** for matching
- 📊 Ranks resumes by **similarity score**
- 💾 Option to **download results** as CSV
- ⚡ Built with a sleek, minimal **Streamlit** frontend

---

## 🛠️ Tech Stack

| Tool       | Description                            |
|------------|----------------------------------------|
| Python     | Core programming language              |
| Streamlit  | For building the web UI                |
| scikit-learn | For TF-IDF vectorization & cosine similarity |
| PyMuPDF    | For parsing text from PDF resumes      |
| Pandas     | For displaying and exporting results   |

---

## 📦  Setup Instructions

1. **Prerequisites**

   Ensure your system has the following installed:

   - Python (>=3.8 recommended)
   - pip (Python package manager)

2. **Clone the repo**
   ```bash
   git clone https://github.com/meetzala2005/Resume-Screening-and-Ranking-System
   cd resume-ranker

3. **Create Virtual Environment (optional but recommended)**
   ```bash
   python -m venv venv
   # Activate it:
   # Windows:
   venv\Scripts\activate
   # Mac/Linux:
   source venv/bin/activate

4. **Install Dependencies**
   ```bash
   pip install -r requirements.txt

5. **Dependencies**

   - Streamlit
   - PyPDF2
   - pandas
   - scikit-learn

   If needed, you can reinstall dependencies using:

   ```bash
   pip install -r requirements.txt

6. **Run the App**
   ```bash
   streamlit run app.py

