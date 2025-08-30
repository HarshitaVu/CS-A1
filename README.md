
# 🛡️ Phishing Detection using Machine Learning

This project implements a **machine learning-based phishing website detection system** using the `Phishing_Legitimate_full.csv` dataset. It applies feature selection, baseline logistic regression, and an optimized random forest classifier to achieve **high accuracy (>95%)** in distinguishing phishing from legitimate websites.

---

## 📌 Features

* Preprocessing and feature selection using correlation analysis & mutual information
* Baseline classification with Logistic Regression
* Optimized detection using Random Forest (Accuracy > 95%)
* Evaluation with confusion matrix, classification report, and feature importance
* Export of trained model and selected features for reproducibility

---

## 📂 Repository Structure

Phishing-Detection-ML/
├── Phishing\_Detection\_Colab.ipynb   — Main Colab notebook
├── outputs/
│   ├── confusion\_matrix.png         — Confusion matrix heatmap
│   ├── classification\_report.txt    — Precision, Recall, F1-score, Accuracy
│   ├── rf\_phishing\_model.pkl        — Saved Random Forest model
│   └── selected\_features.txt        — Ranked feature set used in training
└── report.pdf                       — Final 2-page project report

---

## 🚀 How to Run

1. Open `Phishing_Detection_Colab.ipynb` in **Google Colab**
2. Upload `Phishing_Legitimate_full.csv` dataset
3. Run all cells → Processed outputs will be saved in the `outputs/` folder

---

## 📊 Results

* Logistic Regression provided a reliable baseline
* Random Forest achieved **98% accuracy** with balanced precision and recall
* Confusion Matrix, Classification Report, Trained Model, and Feature List are available in the `outputs/` folder

---

## 👩‍💻 Author

**Harshita**
B.Tech IT-2, CBIT
