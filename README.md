# KNN-Machine-Learning
**PowerPoint:** [Project Presentation](https://docs.google.com/presentation/d/1HM2H3yv5DL9PgcKRwZc01i87o_ZUv0Zndt8AEUi7464/edit?usp=sharing)
**WEKA:** [Download WEKA](https://waikato.github.io/weka-wiki/downloading_weka/)
Build a KNN Model for the Titanic Dataset using Scikit-Learn

## What does main.py do?
This script loads the Titanic dataset, cleans and preprocesses the data, splits it into training and test sets, scales features, tunes and trains a K-Nearest Neighbors (KNN) classifier, makes predictions, evaluates accuracy, and visualizes the results with a confusion matrix.

## How the Code Works
1. **Load Data:** Reads the Titanic dataset from `titanic.csv` using pandas.
2. **Data Cleaning & Feature Engineering:** Removes unnecessary columns, fills missing values, encodes categorical variables, and creates new features for better model performance.
3. **Split Data:** Separates the data into features (`X`) and target (`y`), then splits into training and test sets.
4. **Preprocess Features:** Scales feature values to a common range using MinMaxScaler.
5. **Choose & Tune Model:** Uses K-Nearest Neighbors (KNN) classifier and tunes its hyperparameters with GridSearchCV for best accuracy.
6. **Train Model:** Fits the KNN model to the training data.
7. **Make Predictions:** Predicts survival on the test set.
8. **Evaluate Results:** Calculates accuracy and displays a confusion matrix to show prediction performance.
9. **Visualize:** Plots the confusion matrix using seaborn and matplotlib for easy interpretation.

## How to Run main.py
1. **Create and activate the virtual environment (if not already):**
	```powershell
	python -m venv sklearn-env
	.\sklearn-env\Scripts\Activate.ps1
	```
2. **Install required packages:**
	```powershell
	pip install -r requirements.txt
	```
3. **Run the script:**
	```powershell
	python main.py
	```

## Prerequisites
 - Python 3.x
 - Install all required packages using `requirements.txt`
 - Titanic dataset file named `titanic.csv` in the project directory

## Virtual Environment Setup



```powershell
.\sklearn-env\Scripts\Activate.ps1
```

