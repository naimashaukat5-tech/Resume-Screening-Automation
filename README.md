# Resume-Screening-Automation
📖 Project Overview

This project automates the process of resume screening by extracting skills and experience from candidate resumes and matching them with job descriptions using NLP techniques.

By leveraging spaCy/NLTK for text preprocessing and TF-IDF or BERT embeddings for similarity matching, this system helps recruiters speed up candidate shortlisting with greater accuracy.

🎯 Objectives

Automate resume filtering and candidate-job matching.

Extract skills and experience using spaCy or NLTK.

Perform semantic similarity matching between resumes and job descriptions using TF-IDF or BERT.

Provide a ranked list of suitable candidates for each role.

📂 Dataset

Source: Intern resume database (AI_Resume_Screening.csv)

Description: Contains candidate resumes, job descriptions, and metadata used for training and evaluation.

⚙️ Tech Stack

Python 🐍

Libraries:

pandas, scikit-learn → Data processing & TF-IDF

spaCy / NLTK → Text preprocessing & skill extraction

sentence-transformers (BERT) → Semantic embeddings

tqdm → Progress tracking
