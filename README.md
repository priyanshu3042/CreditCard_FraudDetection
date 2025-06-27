#  Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. It handles real-world challenges such as **class imbalance**, and leverages **XGBoost** for robust classification, along with **SHAP explainability** for model transparency.

---

##  Project Highlights

- Real-world use case from the financial domain
-  Handles highly **imbalanced datasets** using SMOTE
-  Trained using **XGBoost** for high performance
-  Visual and statistical **model evaluation**
-  Uses **SHAP** for feature explainability
-  100% compatible with **Google Colab**

---

##  Dataset

-  Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
-  https://drive.google.com/file/d/1qJmQEbmckVI-hyu0r91XRSMikYUgp_s7/view?usp=sharing
-  284,807 transactions, with 492 fraud cases
-  Highly imbalanced (fraud ≈ 0.17%)

---

##  Technologies & Libraries

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- scikit-learn, imbalanced-learn
- XGBoost
- SHAP (Explainable AI)
- Google Colab

##  Files Included

- `credit_card_fraud_detection.ipynb` – Main notebook with all code, plots, and model outputs  
- `creditcard.csv` – Credit card transaction dataset (to be uploaded manually or via Kaggle)  
- `requirements.txt` – All required Python libraries to run the notebook  
- `.gitignore` – Ignores unnecessary files like `__pycache__`, `.ipynb_checkpoints`, `.DS_Store`, etc.  
- `LICENSE` – MIT License file for open-source sharing and attribution

---

##  Workflow Overview

1. **Load and explore dataset**
2. **Visualize class distribution**
3. **Preprocess and balance using SMOTE**
4. **Train model using XGBoost**
5. **Evaluate using Confusion Matrix, F1, AUC**
6. **Interpret model using SHAP**

---

##  How to Run (Google Colab)

1. Open `credit_card_fraud_detection.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Upload the `creditcard.csv` file from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
3. Run all cells to:
   - Analyze data
   - Train and evaluate model
   - View SHAP explanations

---

##  Example Outputs

###  Class Distribution Plot
Shows severe imbalance between fraud and non-fraud classes.

###  Confusion Matrix & Report
Evaluates true/false positives and model performance.

###  SHAP Beeswarm Plot
Explains which features most influenced fraud predictions.

---

##  Results Summary

| Metric           | Score   |
|------------------|---------|
| Precision (Fraud)| ~87%    |
| Recall (Fraud)   | ~66%    |
| AUC-ROC          | ~0.83   |

> These scores may vary slightly per run, especially with SMOTE and different random states.

---

##  What You’ll Learn

- Handling real-world imbalanced data
- Building interpretable ML models
- Applying SHAP for AI transparency
- End-to-end ML pipeline with EDA → Training → Evaluation → Explainability

## License
## 🛡 License

This project is licensed under the [MIT License](./LICENSE).

**Note:** The dataset used (`creditcard.csv`) is sourced from [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) and is © by the original authors.  
Please refer to Kaggle's terms of use before reusing the dataset.


