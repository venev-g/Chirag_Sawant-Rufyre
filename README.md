#  Team Rufyre

## Team Members
### Chirag Sawant (Lead)
### Raj Nikam
### Parth Sawant

# Rufyre Main Project

## Description
This project involves data preprocessing, feature engineering, and building classification models for drug-target prediction. The goal is to extract useful features, perform necessary transformations, and apply machine learning techniques for predictive analysis.

## Key Features
- Ordinal Encoding on `Drug_high_status` and `Drug_status` columns to prepare categorical data for machine learning models.
- Preprocessing `BIOCLASS` and `FUNCTION` columns for embeddings, using natural language processing techniques.
- Converting sequence data for use in machine learning models.
- **GPU Acceleration**: Leveraged GPU acceleration to speed up the training process using CatBoost.

## Technologies and Libraries Used
- **CatBoost** (`CatBoostClassifier`) - Used for building classification models, with GPU support enabled for faster training.
- **scikit-learn** - Used for modeling and evaluation, including `RandomForestClassifier`, `f1_score`, `train_test_split`, and `LabelEncoder`.
- **NumPy** - Utilized for numerical operations.
- **Pandas** - Used for data manipulation and handling.
- **spaCy** - Used for natural language processing tasks to create embeddings.

## Setup Instructions
1. Clone this repository to your local machine.
2. Install the required dependencies:
   ```bash
   pip install catboost scikit-learn numpy pandas spacy
   python -m spacy download en_core_web_sm




