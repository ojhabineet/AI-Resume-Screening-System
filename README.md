AI-Based Resume Screening System

An AI-powered Resume Screening System that automatically ranks candidates based on job descriptions using NLP and Transformer embeddings.

This system helps recruiters shortlist candidates intelligently by combining:

Semantic similarity (Transformer embeddings)

Skill overlap analysis

Weighted scoring mechanism

Downloadable ranking results

🚀 Features

✅ Upload multiple PDF resumes
✅ Paste any job description
✅ Semantic similarity scoring using transformer models
✅ Skill overlap percentage calculation
✅ Weighted final score (Semantic + Skill match)
✅ Ranked candidate table
✅ Download results as CSV
✅ Clean Streamlit web interface

🧠 How It Works

Resume Text Extraction

Extracts text from uploaded PDF resumes using pdfplumber.

Text Embedding Generation

Uses SentenceTransformer (all-MiniLM-L6-v2) to generate vector embeddings.

Converts resumes and job description into numerical vectors.

Semantic Similarity Matching

Computes cosine similarity between resume embeddings and job description embedding.

Skill Overlap Analysis

Detects predefined job skills in resume text.

Calculates skill overlap percentage.

Weighted Final Score

Final Score = 0.7 × Semantic Similarity + 0.3 × Skill Overlap

Ranking

Candidates are sorted based on Final Score.

🛠 Tech Stack

Python

Streamlit

Sentence Transformers

Scikit-learn

Pandas

NumPy

pdfplumber

PyTorch

📂 Project Structure
AI-Resume-Screening-System/
│
├── app.py
├── requirements.txt
└── README.md
⚙️ Installation (Local Setup)

Clone the repository:

git clone https://github.com/your-username/AI-Resume-Screening-System.git
cd AI-Resume-Screening-System

Install dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app.py

Open browser at:

http://localhost:8501
🌐 Deployment

This project is deployable on:

Streamlit Cloud

Render

Railway

Any cloud server supporting Python

📊 Example Use Cases

HR candidate shortlisting

Technical hiring screening

Startup recruitment automation

Internship candidat
<img width="1896" height="987" alt="Screenshot 2026-02-21 004754" src="https://github.com/user-attachments/assets/5c197501-6ef0-49a5-a8a2-0bea10997a61" />
<img width="1908" height="1038" alt="Screenshot 2026-02-21 004620" src="https://github.com/user-attachments/assets/e275d79a-0b05-452f-9b49-85bfc067a402" />
e ranking





