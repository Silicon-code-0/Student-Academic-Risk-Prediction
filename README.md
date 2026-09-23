# 🎓 Student Academic Risk Prediction

### Advanced Data Mining Techniques — Mini Project

A machine learning and data mining project that analyzes academic and behavioral factors to classify students into **Low, Medium, or High Academic Risk** categories.

## 📌 Project Overview

This project analyzes factors such as attendance, internal marks, assignment completion, study hours, previous CGPA, and backlogs to identify student academic risk patterns.


## 🎯 Objectives

- Analyze student academic and behavioral data.
- Perform data preprocessing and exploratory analysis.
- Identify relationships between features.
- Select relevant features.
- Train and compare classification models.
- Evaluate model performance.
- Analyze important features.
- Provide an interactive prediction interface.

## 🔄 Data Mining Pipeline

```text
Student Dataset
      ↓
Data Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Correlation Analysis
      ↓
Feature Selection
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Feature Importance
      ↓
Risk Prediction

## 📊 Dataset

The project uses a synthetic dataset containing student academic and behavioral information.

**Main Features:**

* Attendance
* Internal Marks
* Assignment Completion
* Study Hours
* Previous CGPA
* Backlogs
* Class Participation

**Target:** Low / Medium / High Risk

## 🤖 Machine Learning Models

The following classification algorithms were implemented:

* Logistic Regression
* Decision Tree
* Random Forest

## 📈 Model Evaluation

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

The detailed results are available in `model_results.csv`.


## 🖥️ Interactive Web Interface

The project includes an interactive HTML interface where users can enter student information and view the predicted academic risk.

**Main file:** `index.html`

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* HTML
* CSS
* JavaScript
* Google Colab
* GitHub


## 📁 Project Structure

Student-Academic-Risk-Prediction/
│
├── index.html
├── Student_Risk_Prediction.ipynb
├── student_data.csv
├── model_results.csv
├── README.md
└── .gitignore

## 🚀 How to Run

### Web Interface

Open `index.html` in any modern web browser.

### Machine Learning Notebook

Open `Student_Risk_Prediction.ipynb` in Google Colab or Jupyter Notebook and run the cells sequentially.


## 🔮 Future Enhancements

* Connect the web interface directly to the trained ML model.
* Deploy the complete application online.
* Add more datasets and machine learning algorithms.
* Add interactive visualizations.
* Add model explainability.
* Store prediction history using a database.

## ⚠️ Disclaimer

This project is developed for **educational purposes only**. The dataset is synthetic and the predictions should not be used for real academic decisions.




