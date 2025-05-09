# Diabetes Prediction: Random Forest vs Neural Networks

This project explores predictive modeling on the PIMA Indian Diabetes dataset using both traditional and deep learning techniques. The goal is to classify whether a patient is likely to develop diabetes based on diagnostic measurements.

## 📊 Objective

To compare the performance of a classic Random Forest classifier versus a Neural Network model in terms of:
- Accuracy
- ROC-AUC Score
- Training time and complexity

## 🧠 Models Used

- **Random Forest Classifier**  
  Baseline model using scikit-learn. Fast to train, interpretable, and delivered a strong ROC-AUC of **0.831**.

- **Neural Network (Keras Sequential Model)**  
  Two dense layers with ReLU activation and sigmoid output. Initially underperformed but improved with extended training (1500 epochs), reaching a ROC-AUC of **0.811**.

## 📈 Results Summary

| Model            | Accuracy | ROC-AUC |
|------------------|----------|---------|
| Random Forest    | 0.755    | 0.831   |
| Neural Network (200 epochs) | 0.682    | 0.782   |
| Neural Network (1500 epochs) | 0.760   | 0.811   |

Although the Neural Network performance improved, the Random Forest model provided competitive results with significantly lower computational cost.

## ⚙️ Technologies

- Python 3.10
- Pandas, NumPy, Seaborn, Matplotlib
- scikit-learn
- TensorFlow / Keras

## 🗂️ Dataset

- [PIMA Indian Diabetes Dataset](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)

## 📌 Key Takeaway

While neural networks are powerful, traditional machine learning models like Random Forest still offer excellent performance with lower complexity. Model choice should always depend on project goals, data characteristics, and resource availability.

## 💡 Author

**Cesar Pedraja**  
[LinkedIn](https://linkedin.com/in/cesarpedraja)  
Data Analyst | Machine Learning Enthusiast  
