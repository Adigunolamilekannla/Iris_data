# 🌸 Iris Flower Classification with Random Forest

This project demonstrates how to build and evaluate a **machine learning classification model** using the **Iris dataset**. We use **Random Forests** combined with **scikit-learn Pipelines** and **hyperparameter tuning** to achieve robust and interpretable results.  

The goal is to classify Iris flowers into three species based on their **sepal length, sepal width, petal length, and petal width**.  

---

## 📂 Project Structure

- ├── iris_rf_classifier.py 
- ├── requirements.txt 
- ├── README.md 


---

## 🚀 Features

- ✅ Uses **Scikit-learn’s built-in Iris dataset**  
- ✅ End-to-end **ML pipeline** (scaling + model)  
- ✅ **Random Forest Classifier** for robust predictions  
- ✅ **Hyperparameter tuning** with GridSearchCV  
- ✅ **Cross-validation** for reliable performance estimates  
- ✅ **Feature importance analysis** for interpretability  
- ✅ **Confusion matrix heatmap** for error analysis  
- ✅ **Learning curve** to visualize bias vs variance  

---

## 📊 Results

- **Best Parameters** found via grid search (example):  
  ```python
  {'max_depth': None, 'min_samples_leaf': 2, 'min_samples_split': 10, 'n_estimators': 50}
