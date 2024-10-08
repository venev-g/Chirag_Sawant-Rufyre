#  Team Rufyre

## 1. Team Members
### Chirag Sawant (Lead)
### Raj Nikam
### Parth Sawant

## 2. Description
This project involves data preprocessing, feature engineering, and building classification models for drug-target prediction. The goal is to extract useful features, perform necessary transformations, and apply machine learning techniques for predictive analysis.

## 3. Key Features
- Ordinal Encoding on `Drug_high_status` and `Drug_status` columns to prepare categorical data for machine learning models.
- Converting sequence data for use in machine learning models.
- **GPU Acceleration**: Leveraged GPU acceleration to speed up the training process using CatBoost.
- Used **SciBert** to extract semantic-embeddings from text columns like `FUNCTION`, `BIOCLASS`

## 4. Technologies and Libraries Used
- **CatBoost** (`CatBoostClassifier`) - Used for building classification models, with GPU support enabled for faster training.
- **scikit-learn** - Used for modeling and evaluation, including `RandomForestClassifier`, `f1_score`, `train_test_split`, and `LabelEncoder`.
- **xgboost** - Used for modeling.
- **NumPy** - Utilized for numerical operations.
- **Pandas** - Used for data manipulation and handling.
- **spaCy** - Used for natural language processing tasks to create embeddings.



## 5. Setup Instructions
1. Clone this repository to your local machine.
2.  Install dependencies using:
```sh
pip install -r requirements.txt
```
3. Install the required dependencies:
```sh
python -m spacy download en_core_web_sm
```



