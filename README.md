🧠 Oral Cancer Analysis & Prediction

This project explores oral cancer risk factors, patterns, and predictive modelling using machine learning and data analysis techniques. It combines descriptive analytics, dimensionality reduction, and model optimization to better understand and predict outcomes related to oral cancer.

🔍 Key Objectives
Analyse risk factors like:
Tobacco use
Alcohol consumption
Betel quid usage
HPV infection
Oral hygiene
Identify patterns across demographics (e.g., gender, country)
Apply machine learning models to predict outcomes such as the survival rate
Improve performance using PCA and hyperparameter tuning

📊 Exploratory Data Analysis

The EDA notebook focuses on:
Distribution of patients by gender and country
Behavioural risk factors (tobacco, alcohol, betel quid)
Health indicators:
Oral lesions
Bleeding
White/red patches
Immune system condition

Visualisations include:
Pie charts
Bar charts
Grouped comparisons

⚙️ Machine Learning Models

Implemented models include:
Decision Tree Regressor
Random Forest
AdaBoost
Extra Trees
XGBoost
Neural Networks:
LSTM
GRU

📈 Evaluation Metrics
R² Score
MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE

🧠 Dimensionality Reduction
Applied PCA (Principal Component Analysis) to:
Reduce feature space
Improve model efficiency
Analyse feature importance

🚀 Optimization
Used Bayesian Optimisation to tune:
Tree depth
Learning rates
Number of estimators

This helps in achieving better performance without brute-force tuning.

🔬 Model Interpretation
Used Permutation Importance (via ELI5) to:
Understand feature impact
Interpret PCA-transformed features

🛠️ Tech Stack
Python
NumPy, Pandas
Matplotlib, Seaborn
Scikit-learn
XGBoost, LightGBM
TensorFlow / Keras
Bayesian Optimization
ELI5

📌 Dataset
The dataset is from the open source platform Kaggle "https://www.kaggle.com/datasets/ankushpanday2/oral-cancer-prediction-dataset/data". 
The dataset includes clinical and lifestyle attributes related to oral cancer.

⚠️ Note: The dataset path in notebooks is local. Update file paths before running.

▶️ How to Run
Clone the repo:
git clone https://github.com/your-username/oral-cancer-analysis.git
cd oral-cancer-analysis
Install dependencies:
pip install -r requirements.txt
Run notebooks:
jupyter notebook

⚠️ Disclaimer
This project is for research and educational purposes only.
It is not intended for medical diagnosis or clinical use.
