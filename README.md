# ⚖️ Gender Bias Detection in Job Descriptions

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
