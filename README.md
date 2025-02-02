# Sentiment Classification using Logistic Regression

## 📌 Overview
This project is a **text-based sentiment classifier** using **Logistic Regression**. The model analyzes input text and classifies it as either **positive** or **negative** sentiment.

## 🏗 Features
- Uses **Bag of Words (BoW)** and **TF-IDF** vectorization.
- Implements **Logistic Regression** for classification.
- Handles **imbalanced data** using `class_weight='balanced'`.
- Includes **stratified train-test splitting** for balanced class distribution.

## 📂 Dataset
The dataset consists of labeled text samples:
- **Positive examples**: Expressions of joy, excitement, or gratitude.
- **Negative examples**: Expressions of frustration, sadness, or disappointment.

## 🔧 Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/your-username/sentiment-classifier.git
cd sentiment-classifier
pip install -r requirements.txt
```

## 🚀 Usage
Run the classifier:
```python
python train.py
```

## 📜 Code Overview
### **1. Data Preprocessing**
- Loads text and sentiment labels.
- Applies **CountVectorizer** or **TF-IDF Vectorizer** for text transformation.
- Splits data into **train and test sets**.

### **2. Model Training**
- Uses `LogisticRegression(class_weight='balanced')` to handle class imbalance.
- Trains the model using **sklearn's** `fit()` function.

### **3. Evaluation**
- Computes **accuracy, precision, recall, and F1-score**.
- Uses `classification_report()` from `sklearn.metrics`.

## 📝 Example Output
```
Accuracy: 0.75
              precision    recall  f1-score   support

    negative       0.75      0.75      0.75         4
    positive       0.75      0.75      0.75         4

   macro avg       0.75      0.75      0.75         8
```

## 🛠 Improvements & Future Work
- Expand dataset for better generalization.
- Experiment with **Deep Learning models** (e.g., LSTMs, Transformers).
- Deploy as a **REST API** using Flask or FastAPI.

## 👨‍💻 Contributing
Feel free to fork this repository and submit a pull request! 🚀

## 📄 License
This project is licensed under the **MIT License**.

---

🔗 **Connect with Me**  
💼 [LinkedIn](https://linkedin.com/in/your-profile)  
📧 Email: your-email@example.com

