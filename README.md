# student-score-regression

This project analyzes student performance data using **Data Analysis** and **Machine Learning** techniques.  
The notebook covers **data cleaning, preprocessing, visualization**, and applies **Regression, Classification, and Clustering** models to extract insights about student academic performance.

---

## 📌 Project Overview
The goal of this project is to understand the factors that affect student performance and to build predictive models based on students’ academic and behavioral data.

The project is implemented entirely in a **Jupyter Notebook** using Python.

---

## 📂 Dataset Description
The dataset contains information about students such as:
- Demographic features (age, gender, school type)
- Study habits (study hours, study method, attendance)
- Academic scores (math, science, English, overall score)
- Final grade (categorical)

The dataset includes **missing values, duplicates, outliers, and inconsistent categorical values**, which are handled during preprocessing.

---

## 🧹 Data Preprocessing
The following steps were applied:
- Handling missing values using **median imputation**
- Dropping columns with excessive missing data
- Removing duplicate records
- Cleaning and standardizing categorical values
- Detecting outliers using the **IQR method**
- Feature scaling using **StandardScaler**

---

## 🤖 Machine Learning Models
### 🔹 Regression
Used to predict the **overall score**:
- Linear Regression
- Random Forest Regressor  
Evaluation metrics:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

### 🔹 Classification
Used to predict the **final grade** of students based on their features.

### 🔹 Clustering
Applied to group students with similar performance and study patterns to uncover hidden structures in the data.

---

## 📊 Visualization
- Distribution plots
- Correlation analysis
- Actual vs Predicted plots for regression models
- Model performance comparison

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure
- `Student_Performance.ipynb` → Main notebook containing all analysis and models
- `student_data_uncleaned.csv` → Raw dataset

---

## ✅ Conclusion
This project demonstrates a complete **machine learning workflow**, starting from raw data to cleaned data, model training, evaluation, and visualization.  
It provides insights into how different factors influence student performance and compares multiple ML approaches.

---

✨ *This project is intended for learning and academic purposes.*
