# 🎓 Student Performance Analysis

This project analyzes student performance data from a Portuguese secondary school. It includes data preprocessing, cleaning, exploratory data analysis (EDA), and a basic machine learning model to predict if a student will pass or fail based on academic and demographic factors.

## 📁 Dataset

Dataset: [UCI Student Performance Dataset](https://archive.ics.uci.edu/ml/datasets/Student+Performance)  
File: `student-por.csv` (manually download and place in the folder)

## 🧰 Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 📊 Project Steps
1. Import Libraries
2. Load and Inspect the Dataset
3. Handle Missing Values
4. Data Cleaning & Preprocessing
5. Exploratory Data Analysis (EDA)
6. Build a Logistic Regression Model
7. Evaluate the Model

## 📁 How to Run
1. Clone the repository
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```
   jupyter notebook student_performance.ipynb
   ```

## ✅ Result
Trained a logistic regression model to predict student success (pass/fail) based on final grade (G3 ≥ 10 means pass). Accuracy varies depending on feature selection and preprocessing.