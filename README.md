## SCT_DS_Task3

### Project Title: Decision Tree Classifier

### Description:
This repository contains the implementation of a Decision Tree Classifier to predict whether a customer will purchase a product or service based on demographic and behavioral data. The project uses the Bank Marketing dataset from the UCI Machine Learning Repository and follows a complete machine learning workflow including data preprocessing, model training, evaluation, and visualization.

### Objectives:
- Load and understand the Bank Marketing dataset  
- Clean and preprocess the dataset  
- Handle categorical and numerical features  
- Build a Decision Tree Classifier model  
- Evaluate model performance  
- Visualize the trained decision tree  
### Dataset:
- Bank Marketing Dataset (UCI Machine Learning Repository)   
- Target Variable: Deposit(yes / no)

### Data Preprocessing Steps:
- Handled dataset formatting issues during loading  
- Cleaned column names and removed unnecessary characters  
- Converted target variable (`y`) into numeric format  
- Converted numerical features to appropriate data types  
- Encoded categorical variables using One-Hot Encoding  
- Used a ColumnTransformer for structured preprocessing  

### Model Used:
- Decision Tree Classifier  
- Criterion: Gini Index  
- Maximum Depth: 5  
- Implemented using Scikit-learn Pipeline  

### Model Evaluation Metrics:
- Accuracy Score  
- Confusion Matrix  
- Classification Report (Precision, Recall, F1-score)  

### Key Findings:
- The Decision Tree model successfully predicts customer purchase behavior  
- Campaign-related features significantly influence predictions  
- The model achieved good accuracy with controlled overfitting  
- Decision Trees provide clear interpretability of decision rules  

### Tools and Libraries Used:
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Google Colab  

### Files in Repository:
1. `SCT_DS_Task3.ipynb` — Complete preprocessing, model training, evaluation, and visualization  
2. `requirements.txt` — Required Python libraries  
3. `README.md` — Project documentation  
### How to Run
1. Open the .ipynb in Colab/GitHub.
2. Run all cells (no external data required).
### Requirements:
1. Clone the Repository : `https://github.com/keerthipriyarayapati/SCT_DS_Task3.git`
2. Install dependencies using:
```pip install -r requirements.txt```
