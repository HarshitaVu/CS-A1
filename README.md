🛡️ Phishing Detection using Machine Learning

This project detects phishing vs legitimate websites using the Phishing_Legitimate_full.csv dataset.

📌 Features

Data preprocessing & feature selection (mutual information, correlations)

Baseline: Logistic Regression

Improved Model: Random Forest (Accuracy > 95%)

Outputs include confusion matrix, classification metrics, saved model, and selected features

📂 Repository Structure

Phishing-Detection-ML/
├── Phishing_Detection_Colab.ipynb # Main notebook
├── outputs/
│ ├── confusion_matrix.png # Confusion Matrix heatmap
│ ├── classification_report.txt # Precision, Recall, F1-score, Accuracy
│ ├── rf_phishing_model.pkl # Saved Random Forest model
│ └── selected_features.txt # Top-N features used
└── report.pdf # Final 2-page project report

🚀 How to Run

Open Phishing_Detection_Colab.ipynb in Google Colab

Upload Phishing_Legitimate_full.csv

Run all cells → Results will be saved in the outputs/ folder

📊 Results

Logistic Regression baseline performed well

Random Forest achieved Accuracy above 95%

Confusion Matrix, Classification Report, Model, and Selected Features are saved in the outputs/ folder

👩‍💻 Author

Harshita
B.Tech IT-2 (CBIT)
