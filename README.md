Resume Screening and Ranking Using NLP & Machine Learning
Overview
This project automates resume screening by categorizing resumes into job roles and ranking them based on relevance to a job description. It leverages NLP techniques and machine learning models to enhance recruitment efficiency.

Key Features
✅ Resume Classification: Categorizes resumes into job roles using models like BERT, DistilBERT, RoBERTa, and ALBERT.
✅ Relevance Ranking: Uses cosine similarity to compare resumes with job descriptions.
✅ Fuzzy TOPSIS Ranking: Ranks resumes within each job role based on weighted criteria (CGPA, skills, degree, internship, gap years).
✅ Text Extraction: Parses resumes from PDFs for structured analysis.

Workflow
Upload Resumes (PDF format)
Text Extraction & Preprocessing (Cleaning, tokenization, vectorization)
Job Role Classification (Best-performing NLP model selected)
Relevance Scoring (Cosine similarity with job description)
Resume Ranking (Fuzzy TOPSIS method applied)
Final Output (Ranked resumes for selection)
Technologies Used
🛠 NLP Models: BERT, DistilBERT, RoBERTa, ALBERT
📊 Ranking Methods: Cosine Similarity, Fuzzy TOPSIS
💻 Libraries: NumPy, Pandas, Scikit-learn, Transformers, PDF parsing tools

Results
🚀 Improved efficiency in resume screening by automating job role classification and ranking, reducing manual effort in hiring.
