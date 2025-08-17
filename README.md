# 📊 Linear Regression Examples with scikit-learn

This repository demonstrates **Linear Regression** applied to two datasets:
 
* 🏡 **Boston Housing Price Prediction** – predicting housing prices based on neighborhood attributes.

Both projects are implemented using **Python & scikit-learn**, and evaluated with metrics such as **MSE, RMSE, and Cross-Validation scores**.

---

## 📌 Key Features

- Handle categorical features using **One-Hot Encoding (dummy variables)**.  
- Train and evaluate **Linear Regression models**.  
- Compute model performance metrics: **MSE** and **RMSE**.  
- Apply **Cross-Validation (CV)** for robust performance measurement.  
- Compare model predictions on **GPA dataset** and **Boston Housing dataset**.  

---

## 🛠️ Technologies Used

- Python 3.x  
- NumPy  
- Pandas  
- scikit-learn  

---

## 📂 Project Structure

```

ml-linear-regression-examples/
│── data/
│   ├── Boston.CSV                   # Boston Housing dataset
│   

│── MLO_Feature_Selection_Boston_LinearRegression.py       # Boston housing prediction script
│── requirements.txt                 # Dependencies
│── README.md                        # Project documentation

````

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/vipunsanjana/MLO-ml-feature-selection-rfe.git
   cd MLO-ml-feature-selection-rfe
````

2. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. (Optional) Explore the combined Jupyter Notebook:

   ```bash
   jupyter MLO_Feature_Selection_Boston_LinearRegression.ipynb
   ```

---

## 📈 Example Outputs

### 🎓 GPA Prediction

* Model intercept & coefficients
* Training **R² score**
* Predictions on test data
* **RMSE** value

### 🏡 Boston Housing Prediction (with CV)

* Fold-wise **RMSE values**
* Average RMSE across folds
* Selected important features (via feature selection methods like RFE/RFECV – optional)

---

## ✅ Future Improvements

* Add **Ridge** and **Lasso Regression** for regularization and comparison.
* Apply **feature scaling** for better performance.
* Add **visualizations** for residuals, errors, and prediction accuracy.
* Extend to **Polynomial Regression** for non-linear patterns.

---

## 👨‍💻 Author

**Vipun Sanjana**
*Software Engineer | Full Stack | ML & DevOps*

---
