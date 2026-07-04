\# Credit Card Fraud Detection



\## Project Overview



This project develops and evaluates machine learning models for detecting fraudulent credit card transactions.



The dataset is highly imbalanced, with fraudulent transactions representing a very small proportion of all transactions. Several machine learning approaches were evaluated and compared.



\## Objectives



\- Explore and understand transaction data

\- Handle class imbalance

\- Build baseline and advanced machine learning models

\- Compare model performance

\- Select the most suitable model for deployment



\## Models Evaluated



1\. Logistic Regression

2\. Logistic Regression + SMOTE

3\. Random Forest

4\. XGBoost



\## Results



| Model | Precision | Recall | F1-Score | ROC-AUC |

|---------|---------:|---------:|---------:|---------:|

| Logistic Regression | 0.82 | 0.65 | 0.73 | 0.9525 |

| Logistic + SMOTE | 0.13 | 0.90 | 0.23 | 0.9775 |

| Random Forest | 0.94 | 0.82 | 0.87 | 0.9630 |

| XGBoost | 0.90 | 0.80 | 0.84 | 0.9601 |



\## Final Model Selection



Random Forest was selected as the preferred model because it achieved the best balance between fraud detection capability and false positive control.



\## Technologies Used



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-Learn

\- Imbalanced-Learn

\- XGBoost



\## Author



Nkosikhona Khoza

