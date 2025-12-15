# Fake News Detection

This project is a simple Fake News Detection system built using Python and Machine Learning.

It takes a news article as input and predicts whether the news is **Fake** or **Real**.

---

## Project Overview

Fake news is a major problem on social media and news platforms.  
This project uses a Machine Learning model to classify news articles based on their text content.

The model is trained using real and fake news datasets and then used in a simple web app.

---

## Technologies Used

- Python  
- Machine Learning (Logistic Regression)  
- Streamlit  
- Pandas, NumPy  
- Scikit-learn  

---

## Dataset

The project uses two datasets:

- `Fake.csv` – contains fake news articles  
- `True.csv` – contains real news articles  

These datasets are used to train the model.

---

## How the Project Works

1. News text is taken as input from the user.
2. Text is converted into numerical form using a vectorizer.
3. A trained Logistic Regression model predicts the result.
4. The output is shown as **Fake** or **Real**.

---

## Files in the Project

- `app.py` – Streamlit app for prediction  
- `app.ipynb` – Model training notebook  
- `vectorizer.jb` – Saved text vectorizer  
- `lr_model.jb` – Trained ML model  
- `requirements.txt` – Required Python libraries  

---

## How to Run the Project

1. Install required libraries:
```bash
pip install -r requirements.txt
