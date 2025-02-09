# Sentiment Analysis: Comparing SVM & Random Forest

## 📌 Project Overview
This project investigates sentiment analysis on financial text using **Support Vector Machines (SVM)** and **Random Forest (RF)**. The objective is to classify text as **positive, neutral, or negative** and evaluate the effectiveness of traditional machine learning models.

## 🚀 What This Project Covers
- **Text Preprocessing:** Tokenization, lemmatization, stopword removal
- **Feature Engineering:** TF-IDF transformation
- **Handling Imbalanced Data:** Using SMOTE for class balancing
- **Model Optimization:** Hyperparameter tuning with GridSearchCV
- **Performance Evaluation:** Precision, recall, F1-score, confusion matrices
- **Data Visualization:** Class distributions and model performance insights

## 📊 Model Performance
| Model          | Accuracy |
|---------------|----------|
| SVM           | 93%      |
| Random Forest | 90%      |

SVM outperforms Random Forest, particularly in handling **neutral sentiment** more effectively. Both models demonstrate strong results, emphasizing the importance of **feature selection and class balancing**.

## 📂 Project Files
- `sentiment_analysis.ipynb` → Jupyter Notebook with full implementation & analysis
- `sentiment_results.csv` → Saved predictions & performance metrics

## 💻 How to Run This Project
### 1️⃣ Install Required Libraries
```bash
pip install pandas scikit-learn matplotlib seaborn nltk imbalanced-learn
```

### 2️⃣ Run the Notebook
Execute `sentiment_analysis.ipynb` in Jupyter Notebook or Google Colab.

## 📈 Key Insights & Takeaways
✔ **Data preprocessing** significantly improves model accuracy.  
✔ **SMOTE balancing** enhances recall for underrepresented classes.  
✔ **Hyperparameter tuning** boosts SVM’s performance noticeably.  
✔ **Visualizations** provide critical insights into misclassifications and model behavior.  

---
🚀 **Found this useful?** Star ⭐ the repository and share it with others!
