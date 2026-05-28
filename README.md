# Fake Review Detection and Sentiment Analysis Project

This project was developed by Elif Serra Uçar,Kerem Döleksöz,Nisa Begüm Burucu,Deniz Kenan Ek and Utku Öztekin for the Data Science course.
The aim of the project is to analyze product reviews and detect whether a review is fake or real by using different Machine Learning and Deep Learning models.


During the project, several Natural Language Processing (NLP) preprocessing steps were applied before training the models. These steps include:

* converting text to lowercase
* removing punctuation marks
* removing stopwords
* text cleaning
* tokenization
* sequence padding
* TF-IDF vectorization

After preprocessing, multiple Machine Learning and Deep Learning models were trained and compared.

## Dataset Information

The original datasets used in this project are relatively large. Therefore, sample datasets are included in this repository.

Original datasets can be accessed from the following links:

English Fake Review Dataset:
https://www.kaggle.com/datasets/sathishcrispsystem/fake-product-review

Turkish Review Dataset:
https://www.kaggle.com/datasets/cebeci/turkishreviews

## Models Used

* Logistic Regression
* Naive Bayes
* LSTM
* GRU
* BiLSTM

## Technologies and Libraries

* Python
* Pandas
* NumPy
* NLTK
* Scikit-learn
* TensorFlow / Keras
* Matplotlib
* Seaborn

## Project Workflow

Raw Review Text
→ Text Cleaning
→ Stopword Removal
→ Tokenization
→ TF-IDF / Sequence Conversion
→ Model Training
→ Performance Evaluation

## How to Run the Project

1. Install the required libraries:
   pip install pandas numpy nltk scikit-learn tensorflow matplotlib seaborn

2. Open the Jupyter Notebook file:
   final_project.ipynb

3. Run all notebook cells step by step.

4. The notebook will:

* preprocess the datasets
* train multiple models
* compare model performances
* generate evaluation outputs and visualizations

## Project Contents

* Fake review detection
* Sentiment analysis
* NLP preprocessing
* Machine Learning models
* Deep Learning models
* Model comparison
* Confusion matrix analysis
* Performance evaluation

This project helped us better understand NLP preprocessing, text classification, fake review detection, 
and the differences between traditional machine learning methods and deep learning approaches on real-world datasets.
