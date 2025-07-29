# 💬 Sentiment Analysis of Healthcare Reviews

A Natural Language Processing (NLP) project that analyzes 4,400+ healthcare customer reviews to extract sentiment insights and uncover patterns in patient feedback using PyTorch and Python.

---

## 🔍 Overview

This project aims to help healthcare providers and administrators better understand patient feedback by classifying textual reviews into **positive**, **negative**, and **neutral** sentiments.

Using a PyTorch-based sentiment classification model, the system processes raw textual data, performs preprocessing, applies tokenization, and classifies sentiment using deep learning techniques.

---

## 🚀 Features

- 🧠 Sentiment classification using supervised NLP models (DL-based)
- 🔍 Text preprocessing with tokenization, stemming, stop word removal
- 📊 Analysis of key opinion themes: wait time, staff behavior, care quality
- 📈 Sentiment distribution insights across hospitals/departments
- 📁 Interactive visualizations (bar plots, word clouds, top keywords)

---

## 🛠️ Tech Stack

| Tool/Library   | Purpose                                 |
|----------------|-----------------------------------------|
| Python         | Core programming language               |
| PyTorch        | Deep learning model training            |
| NLTK / SpaCy   | Text preprocessing                      |
| Pandas         | Data manipulation                       |
| Matplotlib     | Visualization of sentiment trends       |
| Scikit-learn   | Model evaluation (accuracy, F1, recall) |

---

## 📁 Folder Structure

sentiment-healthcare-review-analysis/
│
├── data/
│ ├── reviews.csv # Raw healthcare reviews (~4400)
│
├── notebooks/
│ ├── Sentiment_Model.ipynb # Jupyter Notebook with EDA + training
│
├── models/
│ ├── sentiment_model.pt # Saved PyTorch model
│
├── outputs/
│ ├── plots/ # Bar charts, word clouds, confusion matrix
│
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

## 🧪 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/PrajwalShekar22/sentiment-healthcare-review-analysis.git
cd sentiment-healthcare-review-analysis

**2.Install Dependencies**
bash
Copy
Edit
pip install -r requirements.txt

**3. Run the Notebook**
Launch Jupyter and open:

bash
Copy
Edit
notebooks/Sentiment_Model.ipynb

📈 Key Results
✅ ~79% Positive overall sentiment detected

✅ High performance using F1-score and Precision evaluation

🔍 Identified service quality and wait time as top sentiment themes

📊 Word cloud visualization highlighted key pain points and strengths

📌 Use Cases
📍 Hospitals: Monitor patient sentiment in real time

📬 Feedback Systems: Automate tagging of incoming reviews

🧑‍⚕️ Patient Care Teams: Improve operational processes based on feedback insights

🚀 Future Work
Deploy as a Flask API or Streamlit web app

Connect to real-time review stream (e.g., survey results)

Add multi-label classification for topic modeling

**📜 License**
This project is licensed under the MIT License.

**🙋‍♂️ Author**
Prajwal Gorkhar Chandrashekar
📧 prajwalshekar22@gmail.com
🔗 LinkedIn
🔗 GitHub
