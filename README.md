# resume-analysis.ai

Resume Analysis...

### Steps for creating the project

- Create the Virtual Environment using `python -m venv .venv`
- Activate the Virtual Environment using `source .venv/Scripts/activate`
- Create the .env file to store the API key
- Create the requirements.txt file and add the libraries for installation using `pip install -r requirements.txt`

### Project Synopsis

- We want to create an application that will analyse the resume of the candidate using Gen AI model with the Job Description and provide insights sucg as:-
- ATS Score
- Probability of getting hired
- Am I good fit?
- Keyword analysis
- Swot analysis
- Suggestions for overall improvements

### Architecture

- app.py : Front-End creation and output of Gen AI model.
  --> It will have the feature of capturing information such as Resume and Job Description
- Information that we are capturing is `Resume.pdf` and `job_desc`.
- `pdf.py` that will process the information in pdf and thats why we have installed `pypdf`.
- `analysis.py` that will triangulate the pdf information and the JD and will provide insights and next step.

  # 📄 resume-analysis.ai

🚀 An AI-powered Resume Screening Web App built using **Streamlit** and **Google Gemini (Generative AI)**. It compares a candidate's resume with a job description to provide actionable insights such as ATS score, selection probability, missing keywords, SWOT analysis, and project suggestions.

---

## 🔗 Live Demo

👉 [Click here to try the app on Streamlit Cloud](https://resume-analysis-genai.streamlit.app/)

---

## 🔍 Features

- ✅ **Resume Text Extraction (PDF)**
- 🤖 **LLM-Based Resume Analysis (Gemini API)**
- 📊 **ATS Score Estimation**
- 📈 **Selection Probability**
- ❌ **Missing Keywords**
- 📌 **SWOT Analysis with Actionable Tips**
- 💼 **Recommended ML Projects/Kaggle Competitions**

---

## 🛠️ Tech Stack

| Tool/Library     | Usage                             |
|------------------|-----------------------------------|
| `Streamlit`      | Web app front-end                 |
| `Python`         | Core programming language         |
| `PyPDF`          | PDF text extraction               |
| `Google Generative AI` | Resume & job matching using LLM |
| `dotenv`         | Environment variable management   |

---
