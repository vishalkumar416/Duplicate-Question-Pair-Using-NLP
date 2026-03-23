# 🧠 Duplicate Question Detection System (NLP Project)

## 📌 Overview

This project is an NLP-based web application that identifies whether two questions are duplicates or not. It uses machine learning along with advanced text preprocessing and feature engineering techniques to improve prediction accuracy. The system is deployed using Streamlit, allowing users to input question pairs and get real-time predictions.

---

## 🚀 Features

* Detects duplicate vs non-duplicate questions
* Advanced text preprocessing (cleaning, normalization)
* Feature engineering using linguistic and statistical features
* Fuzzy matching and similarity-based techniques
* Real-time prediction using Streamlit UI

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:** scikit-learn, numpy, pandas, fuzzywuzzy, distance, BeautifulSoup
* **Framework:** Streamlit
* **Model:** Machine Learning (trained classifier)
* **Vectorization:** Bag-of-Words (CountVectorizer)

---

## 📂 Project Structure

```
├── app.py                  # Streamlit application
├── helper.py               # Feature engineering & preprocessing
├── model.pkl               # Trained ML model
├── cv.pkl                  # CountVectorizer
├── stopwords.pkl           # Stopwords file
├── notebooks/              # Jupyter notebooks for experimentation
└── README.md
```

---

## ⚙️ How It Works

1. User inputs two questions
2. Text preprocessing is applied:

   * Lowercasing
   * Removing special characters
   * Handling contractions
   * Removing HTML tags
3. Feature engineering:

   * Basic features (length, word count)
   * Token-based features
   * Fuzzy similarity scores
   * Longest common substring
4. Bag-of-Words vectorization is applied
5. Model predicts whether questions are duplicate or not

---

## 📊 Feature Engineering

* **Basic Features:** Length, word count, common words
* **Token Features:** Word overlap, stopword ratios
* **Length Features:** Absolute difference, substring similarity
* **Fuzzy Features:** QRatio, Partial Ratio, Token Sort Ratio, Token Set Ratio

---

## ▶️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/duplicate-question-detection.git
cd duplicate-question-detection
```

### 2️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```
streamlit run app.py
```

---

## 💡 Usage

* Enter Question 1 and Question 2
* Click on **"Find"**
* Output:

  * ✅ Duplicate
  * ❌ Not Duplicate

---

## 📈 Future Improvements

* Use advanced embeddings (BERT, Sentence Transformers)
* Improve accuracy with deep learning models
* Deploy on cloud platforms (AWS, Heroku)
* Add API support

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

---


**Vishal Kumar**
B-Tech in Artificial Intelligence and Data Science


