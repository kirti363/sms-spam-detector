# 📩 SMS Spam Classification

A Machine Learning project that classifies SMS messages as **Spam** or **Ham (Not Spam)** using Natural Language Processing (NLP) and Machine Learning algorithms.

## 📌 Project Overview

The goal of this project is to automatically identify whether an SMS message is **spam** or **ham**.

The project uses the **SMSSpamCollection** dataset, which contains **5,572 SMS messages** with two columns:

* `label` – Spam or Ham
* `message` – SMS text

## 🚀 Features

* Loads and analyzes the SMS dataset
* Performs text preprocessing using NLP techniques
* Removes stopwords
* Applies text vectorization using **TF-IDF**
* Splits the dataset into training and testing sets
* Trains multiple Machine Learning models
* Evaluates model performance using accuracy, precision, recall, F1-score, and confusion matrix

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* NLTK
* Scikit-learn
* Google Colab

## 🤖 Machine Learning Algorithms

The notebook imports and uses the following classification algorithms:

* Logistic Regression
* Multinomial Naive Bayes
* Support Vector Machine (SVM)

## 🔄 Project Workflow

```text
SMS Dataset
     ↓
Data Loading
     ↓
Data Exploration
     ↓
Text Preprocessing
     ↓
TF-IDF Vectorization
     ↓
Train-Test Split
     ↓
Machine Learning Models
     ↓
Model Evaluation
     ↓
Spam / Ham Classification
```

## 📂 Dataset

The dataset used in this project is:

**SMSSpamCollection.txt**

The dataset is loaded using Pandas with tab-separated values and assigned the columns `label` and `message`.

## 📊 Dataset Information

* Total messages: **5,572**
* Columns: **2**
* Target variable: `label`
* Text variable: `message`
* Missing values: None in the loaded dataset

🤖 Traditional ML Models
Model	Accuracy	Precision (Spam)	Recall (Spam)	F1-Score (Spam)
Logistic Regression	96.77%	1.0000	0.7584	0.8626
Naive Bayes	96.59%	1.0000	0.7450	0.8538
SVM	98.12%	0.9706	0.8859	0.9263

## ▶️ How to Run

### 1. Open Google









Collab.

Upload the notebook to Google Collab.

### 2. Upload the Dataset

Upload `SMSSpamCollection.txt` when prompted by the notebook.

### 3. Run the Notebook

Run the cells from top to bottom to:

1. Load the dataset
2. Explore the data
3. Preprocess the text
4. Convert text into numerical features using TF-IDF
5. Train the Machine Learning models
6. Evaluate the models

## 📁 Project Structure

```text
SMS-Spam-Classification/
│
├── Copy_of_Untitled2.ipynb
├── SMSSpamCollection.txt
└── README.md
```

## 🎯 Objective

The main objective of this project is to demonstrate how **Natural Language Processing and Machine Learning** can be used to automatically detect unwanted or spam SMS messages.

## 👩‍💻 Author

**Kirti Meshram**

B.Sc. Data Science Student
GitHub: @kirti36



