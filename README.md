# 😊 Emotion Classification Using NLP and Machine Learning

## 📌 Project Overview

This project focuses on identifying human emotions from text using Natural Language Processing (NLP) and Machine Learning algorithms.

The system analyzes textual data, performs text preprocessing, converts text into numerical features using TF-IDF vectorization, and predicts emotions using different classification algorithms.

The project also compares multiple machine learning models based on their accuracy.

## 🎯 Objectives

- Understand and analyze textual data.
- Perform text preprocessing using NLP techniques.
- Convert text into numerical representations.
- Build and evaluate machine learning classification models.
- Compare model performance.
- Predict emotions from new text inputs.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- Streamlit

## 🔍 NLP Techniques

The following text preprocessing techniques are implemented:

1. **Tokenization** – Splitting text into individual words or tokens.
2. **Text Cleaning** – Removing unwanted characters and special symbols.
3. **Stemming** – Reducing words to their root forms using Snowball Stemmer.
4. **Stopword Removal** – Removing commonly used words that carry less meaningful information.
5. **TF-IDF Vectorization** – Converting text into numerical features for machine learning.

## 🤖 Machine Learning Algorithms

The project implements and compares five classification algorithms:

- K-Nearest Neighbors (KNN)
- Multinomial Naive Bayes
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Random Forest Classifier

## 📊 Model Evaluation

- Train-Test Split (70% Training and 30% Testing)
- Accuracy Score
- Model Performance Comparison
- Emotion Prediction

## 😊 Emotion Categories

The dataset contains three emotion categories:

- Fear
- Anger
- Joy

## 🌐 Streamlit Web Application

The project includes a Streamlit interface with the following features:

- Dataset upload and preview
- Dataset overview
- Emotion distribution visualization
- Text preprocessing
- Machine learning model training
- Model accuracy comparison
- Emotion prediction from user input

## 📂 Project Structure

```text
Emotion-Classification/
│
├── emotion.ipynb
├── emotion_app.py
├── Emotion_classify_Data.csv
└── README.md
```

## ⚙️ Installation and Execution

**Step 1: Clone the repository**

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 2: Navigate to the project folder**

```bash
cd Emotion-Classification
```

**Step 3: Install required libraries**

```bash
pip install pandas numpy matplotlib seaborn nltk scikit-learn streamlit
```

**Step 4: Run the Streamlit application**

```bash
streamlit run emotion.py
```

## 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Natural Language Processing fundamentals.
- Text preprocessing and feature extraction.
- TF-IDF vectorization.
- Supervised machine learning classification.
- Model evaluation and comparison.
- Building interactive applications using Streamlit.

## 🚀 Conclusion

This project provided practical exposure to combining Natural Language Processing with Machine Learning to solve a text classification problem.

It helped me understand how raw textual information can be transformed into meaningful numerical features and used to identify emotions through machine learning models.

---

**Project Category:** Natural Language Processing | Machine Learning | Text Classification
