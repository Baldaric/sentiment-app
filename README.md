# Sentilytics 🧠📊

**Sentilytics** is a lightweight, offline sentiment analysis desktop app built with Python.  
It allows users to input text manually or upload a CSV file and analyze sentiment using either a fast lexicon-based engine (VADER) or a deep learning-based model (BERT).

---

## ✨ Features

- 🖥️ Simple GUI (Tkinter-based)
- 🧪 Dual sentiment engines:
  - **VADER** for fast, rule-based analysis
  - **BERT** for deep contextual understanding
- 📂 Accepts direct text or CSV input
- 📊 Displays sentiment labels and confidence scores
- 💾 Export results to a new CSV
- 📴 Fully offline — no internet required after setup

---

## 📦 Requirements

Install dependencies via pip:

```bash
pip install -r requirements.txt
```

## 🚀 Quick Start
### Clone this repository:
```bash
git clone https://github.com/yourusername/sentilytics.git
cd sentilytics
```
### Run the app:
```bash
python app.py
```

## 📁 Folder Structure
```
sentilytics/
├── app.py              # GUI logic
├── sentiment.py        # Sentiment analysis engines (VADER + BERT)
├── utils.py            # CSV reading/writing helpers
├── requirements.txt
├── LICENSE
├── README.md
└── example.csv         # Sample CSV for testing
```

## 📜 License
This project is licensed under the MIT License.

## 🙋‍♂️ Author
Created by Baldaric
Feel free to reach out via [LinkedIn](www.linkedin.com/in/affananitya) or [GitHub](https://github.com/Baldaric)

