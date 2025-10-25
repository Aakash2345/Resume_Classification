# 📄 Resume Domain Classification using NLP

This project classifies resumes into professional domains using Natural Language Processing (NLP) techniques, enabling automated resume analysis and keyword insights for recruitment or HR applications.

## 🎯 Objective
To process unstructured resumes, extract meaningful features, and build a machine learning model that accurately predicts professional domains, supported by an interactive Streamlit app.

## 📊 Dataset
- 140 unstructured resumes in PDF/Word formats  
- Standardized all resumes into **.docx** format to ensure **100% data consistency**  
- Preprocessed text data with **tokenization**, **lemmatization**, and **stopword removal**  
- Extracted **3,944 unique terms** using **TF-IDF** for model training

## ⚙️ Approach
- Applied **Complement Naive Bayes (CNB)** classifier with **5-fold cross-validation**  
- Categorized resumes into **eight professional domains** with high accuracy  
- Developed a **Streamlit app** for automated domain prediction and WordCloud-based keyword visualization

## 📈 Insights
- Identified key terms and trends across different professional domains  
- Automated resume classification reduces manual effort and accelerates recruitment processes  
- Visualized domain-specific keywords using WordClouds for immediate insight

## 🧠 Tech Stack
Python • Pandas • NumPy • Scikit-learn • NLTK • TF-IDF • Streamlit • WordCloud • Matplotlib • Seaborn

## 🚀 How to Run
```bash
pip install -r requirements.txt
streamlit run Resume_classification_cloud.py
