# Phishing URL Detection Using Machine Learning

## 📌 Project Overview
This project focuses on detecting phishing URLs using **Machine Learning**. We compare the performance of **Random Forest** and **XGBoost** classifiers to identify fraudulent websites based on various URL-based, domain-based, and content-based features.

## 🗂 Dataset
- The dataset contains multiple features extracted from URLs, such as:
  - **URL Features** (Length, special characters, etc.)
  - **Domain Features** (WHOIS info, age, DNS records)
  - **Content Features** (HTML & JavaScript analysis)
- The target variable: `phishing (1 = Phishing, 0 = Legitimate)`

## 🔧 Data Preprocessing
- **Handled Missing Values** using `SimpleImputer (Median Strategy)`
- **Feature Scaling** with `StandardScaler`
- **Split Data** into **80% training & 20% testing**

## 🚀 Models Used
1. **Random Forest Classifier**
2. **XGBoost Classifier**

## 📊 Performance Metrics
| Model         | Precision | Recall | F1-Score | Accuracy |
|--------------|-----------|--------|----------|----------|
| Random Forest | **0.98**  | 0.98   | 0.98     | **97.07%** |
| XGBoost      | 0.97      | 0.95   | 0.95     | 96.24% |

## 📉 Model Comparison
- **Random Forest outperformed XGBoost**, achieving a **higher accuracy (97.07%)**.
- A **bar chart was generated** to visualize precision, recall, and accuracy for both models.

## 🛠 How to Run
1. Clone the repository:

## 📌 Future Improvements
- Optimize **XGBoost hyperparameters** to improve accuracy.
- Test with **real-time URL detection** in a browser extension.
- Explore **deep learning models** for better feature extraction.

## 📬 Contact
For any questions or contributions, feel free to reach out!

🚀 **Happy Coding!**
