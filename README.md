# 📄 Resume Skills Recommender

**AI-powered tool that enhances resumes by recommending relevant technical skills based on user profiles and datasets.**

This project uses machine learning to analyze user data and suggest skill sets tailored to job descriptions and industry standards. It aims to assist students, job seekers, and professionals in identifying the right skills to add to their resumes—bridging the gap between qualifications and job market expectations.

---

## 🚀 Features

📄 Parse resumes using NLP and TF-IDF

🔍 Extract skills, education, experience

🔁 Match resume with job descriptions using Cosine Similarity

💡 Recommend missing or suggested skills

📈 Predict shortlisting percentage for applied role

🔄 Recommend alternate job roles if resume isn't a good match

---

## 🛠️ Tech Stack
**Programming Language**: Python 3.x

**Libraries**: Pandas, NumPy, Scikit-learn

**Environment**: Jupyter Notebook

**Data Source**: Curated `.csv` file with skill mappings and job-role keywords

---

## 📁 Project Structure

resume-skills-recommender/ 

├── Resume_building_using_ML.ipynb 

├── Resume_skills.csv

├── Software Requirements.pdf

├── User Guide.pdf

├── Resume Skills Recommender PPT.pptx

└── linkedin skill/

---

## 📦 How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/priyanka-bh2/resume-skills-recommender.git
   cd resume-skills-recommender
2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Resume_building_using_ML.ipynb
3. **Follow the notebook instructions**
   - Upload sample data (resume text, job role).
   - Run cells to view recommended skills.
   - Customize and extend as needed.

---

## 📊 Dataset

**Resume_skills.csv**: Contains sample data mapping resumes to associated skills.

**linkedin skill/**: Directory with additional skill data sourced from LinkedIn profiles.

---

## 🔮 Future Enhancements

🌐 **LinkedIn Integration**: Connect with the LinkedIn API to fetch real-time skills from user profiles.
  
🧠 **NLP Integration**: Implement NLP models to extract skills from raw resume text using spaCy or BERT.
  
🌍 **Web Interface**: Build an interactive UI using Flask or Streamlit for non-technical users.
  
📝 **Resume Export**: Add functionality to export resumes in a formatted PDF with recommended skills.
  
🧪 **Job Role Matching**: Match skills against job descriptions to score resume compatibility.
  
📊 **Visualization Dashboard**: Include skill gaps and industry trends using data visualizations.

---

## 📌 Use Cases

🎯 **Job Seekers**: Receive tailored skill recommendations to strengthen resumes.

🧑‍🏫 **Career Counselors**: Help students align their resumes with market-ready skill sets.

🛠️ **ATS Systems**: Integrate into Applicant Tracking Systems for intelligent resume parsing and suggestions.

📚 **EdTech Platforms**: Offer dynamic resume feedback as part of job-prep tools or portals.

👨‍💼 **HR Teams**: Evaluate candidate resumes for missing but desired skills using automation.



