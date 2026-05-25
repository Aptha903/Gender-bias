# ⚖️ Gender Bias Detection in Job Descriptions

## 📌 Project Overview

This project detects **gender bias in corporate job descriptions** using **Natural Language Processing (NLP)** and **Machine Learning techniques**.

The system analyzes job posting text and classifies it as **biased** or **unbiased** based on linguistic patterns. Detecting such bias helps organizations create **more inclusive and fair job advertisements**, promoting equal employment opportunities.

This project supports **Sustainable Development Goal (SDG) 5: Gender Equality**.

---

## 🎯 Problem Statement

Many job descriptions contain subtle gender-biased language that may discourage certain groups from applying.

The objective of this project is to:

- Identify gender-biased language in job descriptions
- Classify job postings as **biased** or **unbiased**
- Improve fairness and inclusivity in recruitment language
- Support equal hiring practices using machine learning

---

## 🎯 Objectives

- Detect gender bias in job descriptions using NLP
- Build a machine learning classification model
- Convert text data into numerical features
- Evaluate model performance using classification metrics

---

## 📊 Dataset Description

The dataset contains job description text along with labels indicating whether the description is biased or unbiased.

### 📌 Dataset Features

| Feature | Description |
|--------|-------------|
| text | Job description content |
| label | Bias classification |

### 🎯 Target Variable

- `label`

Possible values:

- **biased**
- **unbiased**

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- NLTK / Text Processing Libraries
- Jupyter Notebook

---

## 🧠 Machine Learning Model

The project uses **text classification techniques** to detect gender bias.

### Steps in Model Development

1. Text preprocessing
2. Feature extraction using **TF-IDF**
3. Training a classification model
4. Evaluating model performance

### Algorithms Used

- Logistic Regression
- Naive Bayes
- Support Vector Machine (optional)

---

## 🧹 Text Preprocessing

Before training the model, the text data is cleaned using the following steps:

- Convert text to lowercase
- Remove punctuation
- Remove stopwords
- Tokenization
- Text normalization

These steps improve the quality of the input data.

---

## 🔢 Feature Extraction

The processed text is converted into numerical format using:

**TF-IDF (Term Frequency – Inverse Document Frequency)**

TF-IDF helps the model understand how important each word is within the dataset.

---

## 📈 Model Performance

Example evaluation results:

| Metric | Value |
|------|------|
| Accuracy | 0.90 |
| Precision | 0.90 |
| Recall | 0.90 |
| F1 Score | 0.90 |

### 📖 Metric Explanation

- **Accuracy** → Overall correctness of predictions  
- **Precision** → How many predicted biased texts are actually biased  
- **Recall** → Ability of the model to find biased descriptions  
- **F1 Score** → Balance between precision and recall

The results show that the model performs well in identifying biased job descriptions.

---

# ▶️ How to Use This Project

Follow these steps to run the project on your system.

## 1 Clone the Repository

```
git clone https://github.com/YashwanthChowdary19/Gender_Bias_In_Job_Descriptions.git
```

## 2 Run the Jupyter Notebook

```
jupyter notebook
```

Open:

```
logistic_regression_model.ipynb
```

Run all cells to preprocess the data, train the model, and evaluate results.

---

## 🔮 Predict Bias for New Job Description

Example prediction code:

```python
sample_text = ["We are looking for a strong and competitive leader to join our team"]

processed_text = vectorizer.transform(sample_text)

prediction = model.predict(processed_text)

print("Prediction:", prediction[0])
```

Output:

```
biased
```

---

## 🏗️ Project Workflow

1. Load Dataset  
2. Perform Text Preprocessing  
3. Convert Text to Numerical Features (TF-IDF)  
4. Split Dataset into Training and Testing Sets  
5. Train Machine Learning Model  
6. Evaluate Model Performance  
7. Predict Bias in New Job Descriptions  

---

## 🌎 Real-World Applications

- HR recruitment systems
- Job portal platforms
- Corporate hiring analysis
- Diversity and inclusion programs

This system helps organizations **remove biased language from job advertisements**.

---

## 🚀 Future Improvements

- Use advanced NLP models like **BERT**
- Detect multiple types of bias
- Train with larger datasets
- Deploy as a **web application**

---

## 👥 Team Members

- **Team Member 1:** Kothapalli Yashwanth 
- **Team Member 2:** Yuktha V
- **Team Member 3:** Dimple K B  
- **Team Member 4:** Ananya M 
- **Team Member 5:** Vinay mn  
- **Team Member 6:** Anmol C Satakhed
- **Team Member 7:** Madhu Chandrika V  
- **Team Member 8:** Pratham Jaiswal  
- **Team Member 9:** Iram sultana  
- **Team Member 10:** Aptha H P  
- **Team Member 11:** Annapurna Deshmukh  
- **Team Member 12:** Muzamil Pasha N  
- **Team Member 13:** Keerthana A L 
- **Team Member 14:** Kruthanva R  
- **Team Member 15:** Varun R  

---

---

## 📜 License

This project is for educational and research purposes.

---

## 🌍 Sustainable Development Goals

This project supports:

- **SDG 5: Gender Equality**

---

⭐ If you like this project, give it a star on GitHub!
