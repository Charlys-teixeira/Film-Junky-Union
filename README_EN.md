 📖 Description

This project aims to develop machine learning models capable of automatically identifying whether a movie review is positive or negative using Natural Language Processing (NLP) techniques.  
Different classification algorithms were tested and compared, achieving an F1-score above 0.85 on the test set.

## 🗂️ Dataset

- Size: 50,000 labeled reviews (positive = 1, negative = 0)  
- Split: Predefined training and test sets  

## ⚙️ Project Steps

**Data Loading and Cleaning**

- Removal of stopwords and special characters  
- Tokenization and lemmatization  

**Text Vectorization**

- Bag of Words (BoW)  
- TF-IDF  

**Model Training**

- Logistic Regression  
- Random Forest  
- Gradient Boosting (LightGBM)  

**Evaluation**

- Main metric: F1-score  
- Comparison of model performance  

**Validation with Real Examples**

- Creation of fictional reviews for practical validation  

## 📊 Results

- Best performance: Gradient Boosting  
- Test F1-score: > 0.85  
- Models demonstrated good generalization to new texts  

## 🛠️ Technologies Used

- Python 3.10  
- Pandas, NumPy  
- Scikit-learn  
- NLTK / SpaCy  
- LightGBM  

## ✍️ Author

Project developed as part of the Data Science program at TripleTen.
