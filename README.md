# Natural Language Processing with Disaster Tweets

A Natural Language Processing (NLP) project focused on classifying social media posts to determine if they describe real-world disasters. This project compares traditional statistical methods (Logistic Regression) with modern deep learning architectures (BERT).

## 📝 Project Overview
In this project, I used the Kaggle "Natural Language Processing with Disaster Tweets" dataset to build a classification pipeline. The goal is to distinguish between tweets about actual emergencies and those that use disaster-related language metaphorically.

## 🚀 Key Contributions

* **Data Processing & Feature Engineering**:
  * Collected and cleaned disaster-related tweet data.
  * Transformed raw text into numerical data using **TF-IDF** feature vectors.
* **Logistic Regression Baseline**:
  * Constructed a Logistic Regression model with **Cross-Validation** for hyperparameter optimization.
  * Achieved a **79% accuracy rate**.
* **BERT Deep Learning Optimization**:
  * Utilized the **BERT** (Bidirectional Encoder Representations from Transformers) model.
  * Leveraged `BertTokenizerFast` for efficient text tokenization and performance optimization.
  * Achieved a significantly improved **83% accuracy** on the Kaggle leaderboard.

## 📁 Repository Structure

    .
    ├── notebooks/
    │   ├── logistic.ipynb         # Data cleaning and Logistic Regression implementation
    │   └── bert.ipynb             # BERT fine-tuning and evaluation
    ├── outputs/
    │   ├── submission_logistic.csv
    │   └── submission_bert.csv
    └── README.md

## 🛠️ Tech Stack

* **Language**: Python
* **Libraries**: `Scikit-learn`, `Transformers` (Hugging Face), `PyTorch`, `Pandas`

## 📊 Performance Comparison

| Model | Technique | Accuracy |
| :--- | :--- | :--- |
| **Logistic Regression** | TF-IDF + Cross-Validation | **79%** |
| **BERT** | Transformer + Fine-tuning | **83%** |

## 🔗 Dataset Source

The data for this project is provided by the Kaggle competition: [Natural Language Processing with Disaster Tweets](https://www.kaggle.com/c/nlp-getting-started).