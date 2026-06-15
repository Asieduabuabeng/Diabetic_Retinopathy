# COM747 — Diabetic Retinopathy Detection

## Project Overview
A machine learning project to predict the presence of diabetic retinopathy
from clinical retinal measurements. Built as part of the COM747 Data Science
and Machine Learning module at Ulster University.

## Dataset
- **Name:** Diabetic Retinopathy Debrecen
- **Source:** UCI Machine Learning Repository
- **Size:** 1,151 rows, 20 features
- **Task:** Binary classification (0 = no DR, 1 = DR present)
- **License:** CC BY 4.0
- **Link:** https://archive.uci.edu/dataset/329/diabetic+retinopathy+debrecen

## Project Structure
COM747-Diabetic-Retinopathy/

├── data/               # Dataset files (not committed — stored on Google Drive)

├── notebooks/          # Google Colab exploration notebooks

├── src/

│   ├── eda.py          # Exploratory data analysis

│   ├── preprocessing.py # Data cleaning and preparation

│   ├── models.py       # Machine learning model training

│   ├── evaluation.py   # Model evaluation and validation

│   └── utils.py        # Shared utility functions

├── outputs/            # Saved figures and results

└── README.md

## Models Used
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbours (KNN)

## Libraries
pandas

numpy

matplotlib

seaborn

scikit-learn

scipy


## Setup
```bash
# Clone the repo
git clone https://github.com/YOURUSERNAME/COM747-Diabetic-Retinopathy.git

# Create virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter
```

## Team
- Member 1 — EDA, visualisations, Logistic Regression
- Member 2 — Preprocessing, Random Forest, metrics
- Member 3 — Class imbalance, SVM, KNN, tuning
- Member 4 — Cross-validation, evaluation, benchmarking

## Module
COM747 Data Science and Machine Learning
Ulster University — 2025/2026
Submission deadline: 14 August 2026
