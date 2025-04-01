# AI-resume-scanner
AI-Powered Resume Screening and Ranking System
AI Resume Screening & Ranking System

🚀 Overview
This project is an AI-powered resume screening and ranking system built using Streamlit, scikit-learn, and PyPDF2. The application allows users to upload resumes in PDF format, compare them to a given job description, and rank them based on cosine similarity using TF-IDF Vectorization.

✨ Features

✅ Upload multiple PDF resumes.
✅ Enter a job description to compare.
✅ Uses TF-IDF & Cosine Similarity for ranking.
✅ Displays ranked resumes with similarity scores.
✅ Simple & interactive Streamlit UI.

📂 Folder Structure

resume_screening_app/
│── .venv/
│── app.py
│── requirements.txt
│── resume_ranking.ipynb
│── data/
│   ├── sample_resume.pdf 
│── README.md
│── .gitignore

🛠️ Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/yourusername/AI-Resume-Ranking.git
cd AI-Resume-Ranking

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Run the Application

streamlit run app.py

The app will open in your default web browser.

📌 How It Works

1️⃣ Upload PDF resumes using the file uploader.
2️⃣ Enter a job description in the provided text area.
3️⃣ The system extracts text from resumes and converts them into TF-IDF vectors.
4️⃣ The job description is compared against resumes using cosine similarity.
5️⃣ Ranked results are displayed with similarity scores.

🔧 Requirements

Python (3.x)

Streamlit

PyPDF2 (PDF text extraction)

scikit-learn (TF-IDF and cosine similarity)

pandas

Install using:

pip install -r requirements.txt

🎯 End Users

👨‍💼 HR & Recruiters – Automates resume screening for faster hiring.
📈 Hiring Managers – Ranks resumes efficiently for job roles.
🖥️ Job Portals – Enhances resume-job matching accuracy.
🤖 AI Enthusiasts & Students – Learn NLP-based resume analysis.

🔮 Future Scope

✅ Advanced NLP – Integrate BERT/GPT for deeper analysis.
✅ Multi-Format Support – Add DOCX, TXT & OCR for images.
✅ API Integration – Connect with job portals & HR systems.

🔚 Conclusion

This AI-powered Resume Screening & Ranking System addresses the challenge of manual resume screening, which is time-consuming and inefficient. By leveraging TF-IDF and Cosine Similarity, the system automates resume ranking, ensuring fast, objective, and accurate candidate shortlisting. With PDF text extraction, real-time ranking, and easy deployment via Streamlit, this project provides an efficient, scalable, and user-friendly solution for recruiters, hiring managers, and job portals. 🚀



