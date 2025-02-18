# Credit Card Fraud Detection

## 📌 Project Overview
A few months ago, my father lost his credit card at the beginning of May. Unaware of this, we only realized it when the bill arrived at the end of the month, showing unauthorized transactions. This experience led me to explore how **Machine Learning** could be applied to **detect and predict fraudulent credit card transactions**.

## 🎯 Objective
The primary goal of this project is to build a predictive model that can **identify fraudulent credit card transactions** with high accuracy, helping to prevent financial fraud.

## 🛠️ Tech Stack
- **Python**
- **Pandas, NumPy** (Data Processing)
- **Matplotlib, Seaborn** (Data Visualization)
- **Scikit-learn** (Machine Learning Models)

## 🔍 Exploratory Data Analysis (EDA)
Key insights from EDA:
1. The dataset contains **~285,000** transactions with **30 features**, including `time` and `amount`, and a `class` label (fraud or not).
2. The dataset is highly **imbalanced**, with **99.83%** non-fraudulent transactions.
3. **Time** has a **bimodal distribution**, likely due to fewer transactions during nighttime.
4. Transactions **above 10,000 units** were rare and removed from the dataset.
5. Most **fraudulent transactions** were **below 1,000 units**.
6. Fraud occurrence was **independent of the time of day**.

## ⚙️ Model Training & Performance
Several **Machine Learning** models were trained to classify fraudulent transactions:
- **Logistic Regression**
- **k-Nearest Neighbors (k-NN)**
- **Decision Tree**
- **Random Forest**

### 🔥 Best Performing Model
- **Logistic Regression** achieved the highest classification recall of **93%**.
- **Model Evaluation Metrics**:
  - **F1 Score**
  - **Confusion Matrix**
  - **ROC Curve**

## 📊 Results & Conclusion
- **Logistic Regression** provided the best results, making it the most reliable model for fraud detection.
- **Undersampling** was performed due to class imbalance.
- Fraud detection models can significantly **reduce financial risk** by identifying unauthorized transactions in real-time.


## 📜 License
This project is open-source and available under the **MIT License**.

---
Feel free to contribute or raise issues! 😊
