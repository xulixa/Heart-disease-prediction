\# Heart Disease Prediction



Machine learning project for predicting the presence of heart disease using clinical and demographic patient data.



\## Overview



This project explores several machine learning approaches for heart disease classification using the UCI Heart Disease dataset.



The workflow includes:



\- data cleaning and preprocessing,

\- handling missing values,

\- categorical feature encoding,

\- feature scaling,

\- exploratory data analysis,

\- binary classification,

\- multiclass classification,

\- hyperparameter optimization,

\- and model evaluation.



\## Dataset



The project uses the UCI Heart Disease dataset containing 920 patient records and 16 variables.



The dataset includes clinical and demographic features such as:



\- age

\- sex

\- chest pain type

\- resting blood pressure

\- cholesterol

\- fasting blood sugar

\- resting ECG results

\- maximum heart rate

\- exercise-induced angina

\- ST depression

\- slope

\- number of major vessels

\- thalassemia



The target variable is `num`, representing the presence and severity of heart disease.



For binary classification, the target is transformed into:



\- `0` – no heart disease

\- `1` – presence of heart disease



\## Machine Learning Models



The following classification algorithms were evaluated:



\- Decision Tree

\- Gaussian Naive Bayes

\- Random Forest

\- Logistic Regression

\- Support Vector Machine

\- K-Nearest Neighbors



Hyperparameter optimization was performed for selected models using Grid Search and Randomized Search with cross-validation.



\## Evaluation



Models were evaluated using:



\- Accuracy

\- Precision

\- Recall

\- F1 Score

\- Confusion Matrix



Both binary and multiclass classification tasks were investigated.



\## Project Structure



```text

Heart-disease-prediction/

│

├── heart\_disease\_classification.ipynb

├── heart\_disease\_uci.csv

├── requirements.txt

├── .gitignore

└── README.md

```



\## Technologies



\- Python

\- Pandas

\- NumPy

\- Matplotlib

\- Seaborn

\- Scikit-learn

Imbalanced-learn

Jupyter Notebook



\## Team



\- Petar Kuruc

\- Klara Zagajski

\- Lucija Čorak

