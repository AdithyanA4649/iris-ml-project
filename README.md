🌼 Iris Flower Classification using Machine Learning
___________________________________________________________________


📌 Project Overview
This project demonstrates a complete Machine Learning pipeline using the Iris dataset.
It includes data analysis, preprocessing, feature engineering, model training, evaluation, and deployment using a Gradio GUI.
The goal is to classify iris flowers into three species:


Setosa


Versicolor


Virginica
_________________________________________________
Features
_____________________________


✔ Clean and well-structured ML workflow


✔ Exploratory Data Analysis (EDA)


✔ Data Preprocessing & Scaling


✔ Feature Engineering


✔ Multiple ML Models


✔ Model Evaluation & Comparison


✔ Hyperparameter Tuning (GridSearchCV)


✔ Final Model Selection


✔ Interactive GUI using Gradio
___________________________________________________________
*Dataset
_____________________________________________________


Dataset used: Iris Dataset


Total samples: 150

_____________________________________________________
*Features:
_____________________________________________________


Sepal Length


Sepal Width


Petal Length


Petal Width
___________________________________________________________
*Data Loading
____________________________________________________________


Loaded dataset using sklearn.datasets

_____________________________________________________
*Exploratory Data Analysis (EDA)
_______________________________________________________________


Statistical summary (describe)


Data info (info)


Pairplot visualization


Correlation heatmap
______________________________________
*Data Preprocessing
__________________________
Train-test split (80% / 20%)
Feature scaling using StandardScaler
______________________________________________________
*Feature Engineering
______________________________________________________


Created new feature:


petal_ratio = petal_length / petal_width
___________________________________________________________
*Model Building
____________________________________________________________


Trained multiple models:


Logistic Regression


Decision Tree


Random Forest
________________________________________________
*Model Evaluation
________________________________________________________

Accuracy Score


Confusion Matrix


Classification Report
_________________________________________________
*Gradio GUI
_______________________________________________________________

An interactive interface where users can input:


Sepal Length


Sepal Width


Petal Length


Petal Width


👉 Output: Predicted flower species 🌼
_______________________________________
▶️ Running the Application
____________________________________________
python app.py
or run directly in Google Colab
___________________________________________________
📈 Results
______________________________________________
Achieved high accuracy using Random Forest


Improved performance with hyperparameter tuning
_______________________________________________
🎯 Learning Outcomes
_____________________________________________

Understanding ML workflow


Data preprocessing techniques


Feature engineering importance


Model comparison strategies


Hyperparameter tuning


Deploying ML model with GUI
______________________________________
*Author
__________________________________

Adithyan A
