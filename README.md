# Credit-Card-Fraud-Detection

This project leverages machine learning techniques to detect fraudulent credit card transactions. Using the Kaggle dataset [Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud), we apply data preprocessing, class imbalance handling (SMOTE), and build a **Logistic Regression** model to identify fraudulent transactions.

---

## 🧠 Project Highlights

- 🧮 **Dataset**: Contains anonymized transaction features (V1–V28), `Amount`, and `Class` (fraud: 1, non-fraud: 0).
- 📊 **Feature Engineering**: Created `TransactionHour` and `TransactionFrequency` from the `Time` field.
- ⚖️ **Imbalanced Data Handling**: Applied **SMOTE (Synthetic Minority Over-sampling Technique)**.
- ⚙️ **Model**: Logistic Regression from Scikit-Learn.
- 📈 **Evaluation Metrics**:
  - Accuracy: **95.12%**
  - Precision: **97.19%**
  - Recall: **92.94%**
  - F1 Score: **95.01%**

---

## 📁 Project Structure

```bash
├── creditcard_fraud_detection.ipynb  # Main Jupyter notebook
├── README.md                         # Project overview and documentation
└── requirements.txt                  # Required Python packages
```

---

## 🔧 Installation & Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```

2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Download dataset** (if not using Colab):
   - Download from [Kaggle Dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
   - Place `creditcard.csv` in a `data/` folder or update path in notebook accordingly.

4. **Run the notebook**:
   Open the notebook in Jupyter or Google Colab and execute the cells step-by-step.

---

## 📊 Results

| Metric         | Score     |
|----------------|-----------|
| Accuracy       | 95.12%    |
| Precision      | 97.19%    |
| Recall         | 92.94%    |
| F1 Score       | 95.01%    |

---

## 📌 Key Learnings

- How to engineer meaningful features from raw data.
- Importance of handling class imbalance in fraud detection tasks.
- Effectiveness of logistic regression when properly scaled and balanced.
- Evaluation using multiple metrics for imbalanced classification problems.

---

## 📚 Dependencies

```text
pandas
numpy
scikit-learn
imblearn
kagglehub
```


## 💬 Acknowledgements

- Dataset provided by [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).
- Logistic Regression model from [Scikit-learn](https://scikit-learn.org/).
- SMOTE from [imbalanced-learn](https://imbalanced-learn.org/).

---

