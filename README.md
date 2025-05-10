[![MasterHead](https://lh3.googleusercontent.com/pw/AP1GczPPy0Rofqxbl1kXQIYXXfd3zicZ3cCsDQdIIy9MI_1KNVmtn-qBGuiyBPhNoWA0ZNGOWvKGDPXo7GqS9raf_dhgB0YTDka5y_75QL_-eGfK4i_J1i6sp9tH7feCinyynsvPQmJJXWPCB7d6KRuDKJ55=w800-h350-s-no-gm?authuser=0)](https://Avinraj01.io)

# SHL- Grammar Scoring Engine for Voice Samples


🎤 **Predict Grammar Scores from Spoken Audio**
---

## 🧠 Objective
Build a machine learning model that can automatically evaluate spoken audio and assign a **grammar score (1–5)** based on sentence structure and syntax quality.

---

## 🗂️ Dataset Overview

```
Mind Map - Dataset
├── Audio Files (.wav)
│   ├── audios_train/
│   └── audios_test/
├── train.csv
│   └── filename + grammar score
├── test.csv
│   └── filename only
└── sample_submission.csv
    └── sample format for output

---

## ⚙️ Workflow / Pipeline

```
Mind Map - Workflow
1. 🎧 Audio to Text
   └── Using Whisper for transcription
2. ✨ Text Cleaning
   └── Remove punctuation, lowercase, clean spaces
3. 🧮 Feature Extraction
   └── TF-IDF Vectorizer (max 1000 features)
4. 🌲 Model Training
   └── Random Forest Regressor
5. 📊 Evaluation
   └── Pearson Correlation
6. 🧪 Prediction on test set
   └── Generate submission.csv
```

---

## 📈 Evaluation Metric
**Pearson Correlation** used to evaluate prediction quality.

```
📌 Final Public Score: 0.519
```

---

## 📁 Files Included
- `Untitled0.ipynb` - Main notebook with code and explanations
- `submission.csv` - Output file with predictions for test set

---

## 💡 Future Enhancements
```
Mind Map - Improvements
├── Use advanced models (e.g. BERT, XGBoost)
├── Handle diverse accents
├── Use grammar-checking NLP tools
└── Add audio-based features (e.g. fluency, pause detection)
```

---

## 👤 Author
**Crafted with care by [Avin Raj]** ✨

📬 For queries or collaborations, feel free to reach out!
