[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/Vaiishnavi-1350/AI-Resume-Parser/blob/main/resume_parser.ipynb)

# AI-Powered Resume Parser & Ranking System
(BERT-based Resume Ranking System)

**Project Overview**

Recruiters receive hundreds of resumes for a single job posting. Traditional keyword-matching systems fail to understand contextual meaning and often rank candidates inaccurately.
This project builds a context-aware AI Resume Screening System using BERT embeddings, clustering, and weighted similarity scoring to intelligently rank resumes from 0–10 based on relevance to a job description.

**Key Features**

- Semantic Resume Matching using BERT
- Context-aware Similarity Scoring
- Skill-based Feature Engineering
- K-Means Clustering for Domain Grouping
- Weighted Ranking System (0–10 scale)
- Silhouette Score for cluster validation
- Competition-level architecture

**Model Architecture**

1. Text Preprocessing (NLTK)
2. Resume Embedding using Sentence-BERT
3. Skill Extraction & Scoring
4. Cosine Similarity Matching
5. Weighted Score Calculation
6. Resume Ranking

**Tech Stack**

- Python
- NLTK
- Scikit-learn
- Sentence Transformers (BERT)
- Pandas
- NumPy

Dataset
Kaggle Resume Dataset
Columns used:
- Resume
- Category

Scoring Methodology
Final Score = (0.7 × Semantic Similarity Score) +  (0.3 × Skill Match Score)
  Scores normalized and scaled between 0–10.

Evaluation Metric :
- Silhouette Score (Clustering Quality)
- Cosine Similarity (Semantic Matching)

How to Run

1. Open Google Colab
2. Install dependencies
3. Upload dataset
4. Run notebook cells
5. Enter job description
6. View ranked resumes

Why This Project Stands Out ?

Unlike traditional ATS systems that rely on keyword matching, this model:
- Understands contextual meaning
- Reduces keyword stuffing bias
- Provides fair ranking
- Uses modern NLP (BERT embeddings)
- Can be extended to production-level HR systems

**Future Improvements**

- Named Entity Recognition (Experience extraction)
- Resume PDF Parsing
- Education & Certification scoring
- Streamlit Web Application
- Deployment on HuggingFace / AWS
- Bias detection module

Use Cases

- HR Resume Screening
- Talent Acquisition Automation
- Campus Placement Filtering
- AI-based Candidate Ranking Systems


**Author
Vaishnavi Jadhav**

AI & Machine Learning Enthusiast
Focused on NLP & Intelligent Systems
