# Cyberbullying-Classification 🛡️📱

This project focuses on classifying tweets to detect various forms of cyberbullying using machine learning models. It was developed using Google Colab, and the final notebook, models, and data are shared for reproducibility and experimentation.

## 🔍 Problem Statement

Cyberbullying is a growing issue on social media platforms. The objective of this project is to develop a model that can classify tweets into the following categories:
- Religion-based bullying
- Age-based bullying
- Gender-based bullying
- Ethnicity-based bullying
- Not cyberbullying

## 📁 Project Structure

<pre><code>## 📁 Project Structure ``` Cyberbullying-Classification/ ├── CyberbullyingClassification.ipynb <- Colab notebook ├── README.md <- Project overview ├── data/ │ └── dataset.csv <- (Optional: Add if small/public) ├── models/ │ ├── LogisticRegression.pickle │ ├── RandomForest.pickle │ └── XGBoost.pickle └── requirements.txt <- Dependencies (optional) ``` </code></pre>


## 📊 Dataset

- **Total Samples**: 50,000 tweets
- **Features Used**:
  - Tweet length
  - Number of words
  - TF-IDF vectorized text

> ⚠️ *If the dataset is too large to include, provide a download link instead in this section.*

## 🧠 Models Used

- Logistic Regression
- Random Forest Classifier
- XGBoost Classifier

All models were trained, evaluated, and the best-performing ones were saved using `pickle` for future use.

## 🛠️ Tech Stack

- Python 3.x
- Google Colab
- Scikit-learn
- XGBoost
- Pandas, NumPy, Matplotlib, Seaborn
- TF-IDF Vectorization

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/faiz0407/Cyberbullying-Classification.git
   cd Cyberbullying-Classification
