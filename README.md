# 📄 Resume / Candidate Screening System (FUTURE_ML_03)

## 🚀 Project Overview

This project is developed as part of the Machine Learning Internship Task 3 by Future Interns.

The goal of this project is to build a Resume Screening System using Machine Learning and Natural Language Processing (NLP).

The system automatically compares candidate resumes with job descriptions, extracts important skills, calculates similarity scores, identifies missing skills based on job-role fit.

This helps recruiters save time and improves hiring decisions.

---

## 🎯 Objective

The main objective of this project is to:

- Read resume text data
- Extract important skills and keywords
- Compare resumes with job descriptions
- Calculate resume-job matching score
- Identify missing required skills

This project simulates how real ATS (Applicant Tracking System) works in companies.

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Development Tools
- Jupyter Notebook
- VS Code
- GitHub

### Libraries Used
- Pandas
- NumPy
- Sentence Transformer
- Scikit-learn

---

## 📁 Dataset Used

### 1. Resume Dataset
Source:
https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset

Contains:
- Resume text
- Resume category
- Multiple job profiles

### 2. Job Description Dataset
Source:
https://www.kaggle.com/datasets/PromptCloudHQ/us-jobs-on-monstercom

Contains:
- Job title
- Job description
- Required skills
- Experience details

---

## ✨ Key Features

✔ Resume text cleaning and preprocessing

✔ Skill extraction using NLP

✔ Job description parsing

✔ Sentence Embedding vectorization

✔ Cosine similarity score calculation

✔ Missing skills identification

✔ Business-friendly output for recruiters

---

## ⚙️ Project Workflow

### Step 1: Data Collection
Load Resume Dataset and Job Description Dataset

### Step 2: Text Preprocessing
- Lowercase conversion
- Remove stopwords
- Remove punctuation
- Remove special characters

### Step 3: Skill Extraction
Extract important skills from:
- Resume text
- Job descriptions

### Step 4: Feature Engineering
Convert text into numerical vectors using:
- Sentence Embedding Vectorizer

### Step 5: Similarity Calculation
Use:
- Cosine Similarity

To calculate:
Resume Match Score

### Step 6: Missing Skills Detection
Identify:
Skills required in job description but missing in resume

---

## 📊 Example Output

<img src="Screenshot%20(143).png">

Recommendation:
Good fit for the role but needs improvement in Deep Learning and NLP.

---

## 📈 Model Evaluation

Evaluation includes:

- Similarity Score Analysis
- Skill Match Percentage
- Candidate Ranking Logic
- Resume Relevance Analysis

Optional:
- Confusion Matrix
- Candidate Comparison Graph

---

## 💼 Business Use Case

This project helps:

- HR teams shortlist candidates faster
- Reduce manual screening effort
- Improve hiring accuracy
- Identify skill gaps before interviews
- Build better recruitment pipelines

Useful for:
- Recruiters
- HR Managers
- Hiring Teams
- HR-Tech Startups

---

## 📂 Project Structure

FUTURE_ML_03/  
├── notebooks    
├── README.md  

---

## 🔥 Future Improvements

- PDF Resume Parsing
- Web-based ATS Dashboard
- Advanced NLP using BERT
- Weighted skill importance
- Real-time recruiter interface
- AI-powered candidate recommendations

---

## 👨‍💻 Author

Manish Raikwar

Machine Learning Intern

Future Interns

---

## 🔗 Connect With Me

LinkedIn: www.linkedin.com/in/manish-raikwar-209878264

---

## 🙌 Acknowledgement

Special thanks to Future Interns for providing this internship opportunity and practical industry-level Machine Learning tasks.

This project helped in understanding real-world NLP applications in recruitment systems.

---
