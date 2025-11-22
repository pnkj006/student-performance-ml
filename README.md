# student-performance-ml

# 📘 Student Performance Prediction (Multiple Linear Regression)

This project builds a **Multiple Linear Regression model** to predict a student’s final performance score using academic and lifestyle-related factors.  
The dataset is sourced from Kaggle and contains features such as study hours, sleep hours, previous scores, exam practice, and extracurricular activities.

---

## 📊 Dataset
**Source:** Kaggle  
**Link:** https://www.kaggle.com/datasets/nikhil7280/student-performance-multiple-linear-regression  
**Dataset Name:** *Student Performance - Multiple Linear Regression*

### **Features included:**
- `Hours Studied`
- `Previous Scores`
- `Extracurricular Activities` (Yes/No)
- `Sleep Hours`
- `Sample Question Papers Practiced`

### **Target Variable:**
- `Performance` (final score)

---

## 🚀 Features of This Project
- Complete **data cleaning & preprocessing**
- Conversion of categorical values into numeric form
- Exploratory Data Analysis (pairplots, correlations)
- Train/Test split
- Feature scaling using `StandardScaler`
- Linear Regression model training
- Evaluation metrics (MSE, MAE, RMSE, R², Adjusted R²)
- Visualization of predictions and residuals
- Prediction on new custom inputs

---

## 🛠️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📚 Steps Performed in the Notebook

### **1️⃣ Data Loading & Inspection**
- Checked data types, missing values, and dataset info.
- Converted categorical values (`Yes` / `No`) to 1 / 0.

### **2️⃣ Exploratory Data Analysis**
- Pairplots to visualize relationships.
- Correlation heatmap to check feature relationships.

### **3️⃣ Preprocessing**
- Standardizing features using `StandardScaler`
- Splitting dataset into train and test sets (90% training / 10% testing)

### **4️⃣ Model Training**
- Used `LinearRegression()` from Scikit-learn.
- Fitted model using standardized data.

### **5️⃣ Model Evaluation**
Metrics used:
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**
- **Adjusted R² Score**

### **6️⃣ Visualization**
- Actual vs predicted scatter plot
- Residual distribution plot

### **7️⃣ Prediction on New Data**
Example input:
```python
{
    "Hours Studied": 7,
    "Previous Scores": 95,
    "Extracurricular Activities": 1,
    "Sleep Hours": 7,
    "Sample Question Papers Practiced": 10
}
