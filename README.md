# Titanic Survival Prediction — Logistic Regression with Python

## Project Description

This project performs Exploratory Data Analysis (EDA), data preprocessing, and builds a Logistic Regression model on the Titanic dataset. The objective is to analyze the factors affecting passenger survival and predict whether a passenger survived or not using machine learning.

---

## Dataset

Dataset: `titanic_train.csv`

Target Variable:

* Survived

Features used in the analysis include:

* Passenger Class (Pclass)
* Sex
* Age
* Number of Siblings/Spouses Aboard (SibSp)
* Number of Parents/Children Aboard (Parch)
* Fare
* Embarked

---

## Project Workflow

### 1. Exploratory Data Analysis (EDA)

The notebook includes:

* Missing value analysis using heatmaps
* Survival distribution analysis
* Survival comparison based on Sex and Passenger Class
* Age distribution analysis
* SibSp distribution
* Fare distribution

---

### 2. Data Preprocessing

The following preprocessing steps are performed:

* Handling missing values
* Dropping unnecessary columns
* Creating dummy variables for categorical features:

  * Sex
  * Embarked
* Combining processed features into the final dataset

---

### 3. Machine Learning Model

Algorithm:

* Logistic Regression

Train/Test Split:

* Training and testing data created using `train_test_split`

Steps:

1. Split the dataset into training and testing sets.
2. Train the Logistic Regression model.
3. Predict survival on the test dataset.
4. Evaluate model performance.

---

## Model Evaluation

The notebook evaluates the model using:

* Classification Report
* Precision
* Recall
* F1-Score

---

## Concepts Used

* Exploratory Data Analysis (EDA)
* Missing Value Analysis
* Data Visualization
* Feature Engineering
* Dummy Variable Encoding
* Train/Test Split
* Logistic Regression
* Classification Metrics

---

## Project Structure

```text
Titanic-Logistic-Regression/
│
├── 01-Logistic Regression with Python.ipynb
├── titanic_train.csv
└── README.md
```

---

## How to Run

### Requirements

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Steps

1. Clone this repository.
2. Place `titanic_train.csv` in the project folder.
3. Open `01-Logistic Regression with Python.ipynb`.
4. Run all cells from top to bottom.

---

## Author

Meet Tailor — Data Science Learner

GitHub: https://github.com/MeetTailor-Data

---

## License

Created for learning and educational purposes only.
