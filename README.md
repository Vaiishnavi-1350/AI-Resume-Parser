[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/Vaiishnavi-1350/AI-Resume-Parser/blob/main/AI_Resume_Parser.ipynb)

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


**System Architecture**

The following architecture diagram illustrates the workflow of the AI-based Resume Parser system.
Workflow Explanation
1. Resume Dataset Input
The system begins by loading a resume dataset containing candidate resumes and their respective categories.
2. Text Preprocessing
Resume text is cleaned using Natural Language Processing techniques such as:
- Lowercasing
- Removing punctuation and numbers
- Stopword removal
- Lemmatization using NLTK
3. Feature Representation (BERT Embeddings)
Cleaned resumes are converted into semantic embeddings using a Sentence-BERT model.
This allows the system to understand the contextual meaning of words rather than simple keyword matching.
4. Skill Extraction Module
Important technical skills such as Python, Machine Learning, NLP, SQL, and Deep Learning are extracted from resumes to generate a skill score.
5. Similarity Matching
The job description is converted into an embedding and compared with resume embeddings using cosine similarity to measure relevance.

6. Weighted Scoring System
The final ranking score is calculated by combining:
- Semantic similarity score
- Skill match score
7. Candidate Ranking
Resumes are ranked from 0 to 10 based on their suitability for the job role.

**Architecture Components** 

- Dataset Loader

- Text Preprocessing Engine

- NLP Embedding Model

- Skill Extraction Module

- Similarity Matching Engine

- Candidate Ranking System

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
