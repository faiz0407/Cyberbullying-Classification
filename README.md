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

```text
Cyberbullying-Classification/
├── CyberbullyingClassification.ipynb    # Colab notebook
├── README.md                            # Project overview
├── data/
│   └── dataset.csv                      # (Optional: Add if small/public)
├── models/
│   ├── LogisticRegression.pickle
│   ├── RandomForest.pickle
│   └── XGBoost.pickle
└── requirements.txt                     # Dependencies (optional)
```

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

## Web Interface for Cyberbullying Classification

To enhance usability, a simple **web interface** was designed to allow users to input tweets and receive an instant classification indicating whether the tweet contains cyberbullying or not.

### Features
- Input a tweet directly through the webpage.
- Classify the tweet as **Bullying** or **Not Bullying** using the trained machine learning models.
- User-friendly and clean interface designed for easy interaction.

### Current Status
- The web interface is **not currently deployed online**, so there is no live URL available.
- The full source code for the interface is included in the `web_interface/` directory of this repository.
- This allows users or collaborators to run the interface locally or extend it for future deployment.
