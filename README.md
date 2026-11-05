
# 🎯 Resume Job Match Scorer

### An NLP-Based Resume and Job Description Matching Application

Resume Job Match Scorer is a Python-based web application built using **Streamlit and Natural Language Processing (NLP)**. It helps job seekers evaluate how closely their resume matches a particular job description.

Users can upload their resume in PDF format, paste a job description, and receive a similarity score with visual feedback.

## 🚀 Features

- 📄 Upload resumes in PDF format.
- 📝 Enter job descriptions.
- 🔍 Extract text from PDF resumes.
- 🧹 Clean and preprocess text using NLP.
- 🤖 Apply TF-IDF vectorization.
- 📊 Calculate similarity using Cosine Similarity.
- 📈 Display match percentage with a visual gauge.
- ✅ Show match verdict:
  - Low Match
  - Good Match
  - Excellent Match

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Streamlit | Web Application |
| PyPDF2 | PDF Text Extraction |
| NLTK | Text Processing |
| Scikit-learn | TF-IDF and Cosine Similarity |
| Matplotlib | Data Visualization |

## ⚙️ How It Works

1. Upload your resume in PDF format.
2. Paste the job description.
3. Extract text from the uploaded resume.
4. Preprocess both documents.
5. Convert text into numerical vectors using TF-IDF.
6. Calculate similarity using Cosine Similarity.
7. Generate a match score between 0 and 100.
8. Display the result with a visual representation.

## 💻 Installation and Setup

**Step 1: Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

**Step 2: Navigate to the project folder**

```bash
cd Resume-Job-Match-Scorer
```

**Step 3: Install dependencies**

```bash
pip install streamlit matplotlib scikit-learn PyPDF2 nltk
```

**Step 4: Run the application**

```bash
streamlit run app.py
```

*Note: Replace `app.py` with your actual application filename if it is different.*

## 📸 Application Workflow

**Input:** Resume PDF + Job Description

**Processing:** PDF Extraction → Text Preprocessing → TF-IDF → Cosine Similarity

**Output:** Resume Match Score + Visual Feedback

## 🔮 Future Improvements

- Extract missing keywords from job descriptions.
- Add OCR support for scanned resumes.
- Implement advanced semantic similarity.
- Provide personalized resume improvement suggestions.
- Add ATS-based resume analysis.
- Improve application performance using caching.

## ⚠️ Disclaimer

This application provides a text-similarity score and does not guarantee job selection or measure a candidate's actual skills and qualifications.

## 👩‍💻 Author

**Your Name**

GitHub: https://github.com/Shivangimishra0

LinkedIn: www.linkedin.com/in/shivangi-mishra-b8a601333

---

⭐ If you find this project useful, consider giving it a star!