# Heart Disease Prediction Using Machine Learning

## 1. Project Objective
The objective of this project is to compare machine learning
models for binary classification using the UCI Heart Disease dataset.

## 2. Dataset
- Source: UCI Machine Learning Repository
- Dataset: Cleveland Heart Disease subset
- Records: 303
- Input features: 13
- Target: Binary classification (0 or 1)

Target 0 represents an original target value of 0.
Target 1 represents an original target value greater than 0.

## 3. Technologies
- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab

## 4. Data Preprocessing
- Checked missing values and duplicate records.
- Split the dataset into training and testing sets.
- Used median imputation for numerical features.
- Used most-frequent imputation for categorical features.
- Standardized numerical features.
- Applied one-hot encoding to categorical features.
- Used a pipeline to reduce data leakage risk.

## 5. Machine Learning Models
1. Logistic Regression
2. Random Forest
3. Decision Tree

## 6. Reported Results

| Model | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 0.885 | 0.839 | 0.929 | 0.881 | 0.966 |
| Random Forest | 0.869 | 0.833 | 0.893 | 0.862 | 0.945 |
| Decision Tree | 0.738 | 0.700 | 0.750 | 0.724 | 0.745 |

These results are based on the reported notebook output.
Verify them against the final saved evaluation results.

## 7. Conclusion
Logistic Regression achieved the strongest reported performance
among the three models on the held-out test set.

## 8. Limitations
The dataset is small and may not represent other populations.
The reported performance does not establish clinical validity.

## 9. Disclaimer
This project is for educational and portfolio purposes only.
It is not a medical diagnostic tool and must not be used for
medical decisions.

## 10. Dataset Reference
https://archive.ics.uci.edu/dataset/45/heart+disease
