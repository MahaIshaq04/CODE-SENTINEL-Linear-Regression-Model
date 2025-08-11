# Task 1 - CODE SENTINEL Virtual Internship (Artificial Intelligence)

## 📌 Overview
This repository contains the implementation of **Task 1** for the **CODE SENTINEL Virtual Internship (Artificial Intelligence Track)**.  
The task involves building a **Linear Regression** model to predict housing prices using Python and scikit-learn, with proper visualization using matplotlib.

---

## 🛠️ Technologies Used
- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn (optional, for better plots)

---

## 📂 Dataset
The dataset used is similar to the **Boston Housing dataset**, containing information such as:
- `RM` — Average number of rooms per dwelling  
- `LSTAT` — Percentage of lower status population  
- `MEDV` — Median value of owner-occupied homes (target variable)  
- Additional features like `CRIM`, `NOX`, `TAX`, etc.

---

## 🚀 Steps Implemented
1. **Load and Inspect Dataset**  
   - Checked dataset shape, data types, and missing values.
   
2. **Data Preprocessing**  
   - Filled missing values using **mean imputation**.  
   - Removed outliers to improve model performance.

3. **Feature Selection**  
   - Selected 2 key features: `RM` and `LSTAT`.

4. **Data Splitting**  
   - Split dataset into **training (80%)** and **testing (20%)** sets.

5. **Model Training**  
   - Trained a **Linear Regression** model using scikit-learn.

6. **Model Evaluation**  
   - Calculated **Mean Squared Error (MSE)** and **R² Score**.  
   - Visualized results with scatter plots and regression lines.  
   - Added **3D visualization** for better understanding.

---

## 📊 Results
- **Mean Squared Error (MSE):** `13.61`  
- **R² Score:** `0.73`  
- The model shows a good fit with the selected features.

---

## 📷 Visualizations
📌 Example outputs:

- **Scatter Plot with Regression Line**  
- **3D Plot of RM, LSTAT vs MEDV**

*(Add screenshots here when pushing to GitHub)*

---

## 📜 How to Run
```bash
# Clone this repository
git clone https://github.com/yourusername/task1-code-sentinel.git

# Navigate to the folder
cd task1-code-sentinel

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook Task1_LinearRegression.ipynb