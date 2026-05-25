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
⚖️ Gender Bias Detection in Job Descriptions

An NLP and Machine Learning system that detects and classifies 
gender-biased language in job descriptions, promoting fair and 
inclusive hiring practices.

---

## 🎯 Problem Statement
Certain words in job descriptions unconsciously discourage 
specific groups from applying. This project uses machine learning 
to automatically detect and flag gender-biased language, helping 
organizations write more inclusive job postings.

---

## ✨ Features
- 🔍 Detects gender-biased language in job descriptions
- 🏷️ Classifies text as **Biased** or **Unbiased**
- 📊 Achieves ~90% classification accuracy
- 🧹 Full NLP preprocessing pipeline
- ⚖️ Handles class imbalance using upsampling

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Scikit-learn | Logistic Regression model |
| NLP | Text preprocessing & analysis |
| TF-IDF | Feature extraction |
| Pandas & NumPy | Data handling |
| Matplotlib | Visualization |

---

## 📁 Project Structure
```
gender-bias-detector/
│
├── dataset/
│   └── job_descriptions.csv     # Kaggle dataset
│
├── preprocessing.py             # Text cleaning & TF-IDF
├── model.py                     # Logistic Regression model
├── evaluate.py                  # Metrics & confusion matrix
├── predict.py                   # Predict on new input
├── requirements.txt             # Dependencies
└── README.md
```

---

## 🔄 Workflow

```
Raw Job Description Text
        ↓
Text Cleaning & Lowercase
        ↓
Stopword Removal & Lemmatization
        ↓
Class Imbalance Handling (Upsampling)
        ↓
TF-IDF Feature Extraction
        ↓
Logistic Regression Model
        ↓
Biased / Unbiased Classification
```

---

## 📊 Model Performance

| Metric | Score |
|---|---|
| Accuracy | ~90% |
| Precision | High |
| Recall | High |
| F1-Score | High |

- Balanced performance for both Biased and Unbiased classes
- Evaluated using confusion matrix analysis

---

## ⚙️ Installation & Setup

```bash
# Clone the repository
git clone https://github.com/Aptha903/gender-bias-detector.git
cd gender-bias-detector

# Install dependencies
pip install -r requirements.txt

# Run prediction
python predict.py
```

---

## 💡 How It Works
1. Input a job description as text
2. The system cleans and preprocesses the text
3. TF-IDF converts text into numerical features
4. Logistic Regression classifies it as Biased or Unbiased
5. Output is returned with classification result

---

## 🔮 Future Scope
- Suggest neutral alternatives for biased words
- Browser extension for real-time job post analysis
- Support for multiple languages
- Deep learning model for improved accuracy
- Integration with job posting platforms

---

## 📜 Dataset
- Source: Kaggle
- Labels: Biased / Unbiased
- Created using gender-associated word list
- Used for supervised learning

---

## 👩‍💻 Author
**Aptha H P**
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/aptha-hp-9951242a6)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:apthagowda258@gmail.com)
