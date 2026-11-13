# Fake News Classification Using NLP and Machine Learning

A machine learning project that uses Natural Language Processing (NLP) techniques to classify news articles as **Fake** or **Real**.

## Overview

Fake news can spread rapidly through digital platforms and influence public opinion. This project aims to build a text classification system that analyzes news articles and predicts whether an article is fake or real.

The system uses TF-IDF for text feature extraction and supervised machine learning algorithms for classification.

**Note:** This project is an educational text classification system, not an authoritative fact-checking tool.

## Objectives

- Understand and preprocess textual news data.
- Apply NLP techniques for text representation.
- Extract features using TF-IDF.
- Train and compare multiple machine learning classifiers.
- Evaluate model performance using standard classification metrics.
- Build an interactive web application using Streamlit.

## Tech Stack

| Category | Technologies |
|---|---|
| Language | Python |
| Environment | uv |
| Data Processing | Pandas, NumPy |
| NLP | NLTK, Scikit-learn |
| Feature Extraction | TF-IDF |
| Machine Learning | Naive Bayes, Logistic Regression, Random Forest |
| Visualization | Matplotlib, Seaborn |
| Frontend | Streamlit |
| Model Storage | Joblib |

## Dataset

**Dataset:** WELFake Dataset

The dataset contains labelled news articles used to train and evaluate the classification models.

- Source: [WELFake Dataset – Zenodo](https://zenodo.org/records/4561253)
- File name: `WELFake_Dataset.csv`

Download the dataset and place it inside the `data/` directory.

## Project Structure

```text
fake-news-classifier/
│
├── data/
│   └── WELFake_Dataset.csv
│
├── models/
│
├── notebooks/
│
├── main.py
├── train.py
├── app.py
│
├── pyproject.toml
├── uv.lock
└── README.md
```

## Installation and Setup

### 1. Install uv

If uv is not installed:

```bash
pip install uv
```

Alternatively, follow the official installation guide:

https://docs.astral.sh/uv/

### 2. Clone the repository

```bash
git clone <your-repository-url>
cd fake-news-classifier
```

### 3. Install dependencies

```bash
uv sync
```

### 4. Add the dataset

Place `WELFake_Dataset.csv` inside the `data/` directory.

## Model Training

Train the machine learning models using:

```bash
uv run train.py
```

The project will explore and preprocess the dataset, extract text features using TF-IDF, and train the selected classification algorithms.

## Run the Web Application

Launch the Streamlit application:

```bash
uv run streamlit run app.py
```

## Machine Learning Algorithms

The project aims to implement and compare:

1. **Multinomial Naive Bayes** – A probabilistic classifier commonly used for text classification.
2. **Logistic Regression** – A linear classification algorithm for predicting class probabilities.
3. **Random Forest** – An ensemble learning algorithm based on multiple decision trees.

## Evaluation Metrics

The models will be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Actual evaluation results will be added after model training.

## Team Members

**Group 1 – B.Tech Information Technology, IIIT Una**

- Ayush Rai
- Deep Shekhar Singh
- Durgesh Singh

## Project Status

🚧 Currently under development.

## Disclaimer

This project is developed for academic and educational purposes. Predictions should not be treated as definitive verification of the authenticity of a news article.

## License

This project is intended for educational and academic use.