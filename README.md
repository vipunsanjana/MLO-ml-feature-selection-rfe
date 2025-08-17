
# 📊 Linear Regression with Feature Selection (scikit-learn)

This repository demonstrates **Linear Regression with Feature Selection** on the  
🏡 **Boston Housing Price Prediction dataset** – predicting housing prices based on neighborhood attributes.

We apply **Recursive Feature Elimination (RFE)** and  
**Recursive Feature Elimination with Cross-Validation (RFECV)** using **scikit-learn**.

---

## 📌 Key Features

- Perform **feature selection** using RFE and RFECV  
- Train and evaluate **Linear Regression models**  
- Compute evaluation metrics: **MSE** and **RMSE**  
- Apply **Cross-Validation (CV)** for robust performance measurement  
- Compare feature subsets for optimal model accuracy  

---

## 🛠️ Technologies Used

- Python 3.x  
- NumPy  
- Pandas  
- scikit-learn  

---

## 📂 Project Structure

```

ml-feature-selection-rfe/
│── data/
│   ├── Boston.CSV                     # Boston Housing dataset

│── MLO\_Feature\_Selection\_Boston\_LinearRegression.ipynb # Jupyter Notebook 
│── requirements.txt                   # Dependencies
│── README.md                          # Documentation

````

---

## 🚀 How to Run

1. **Clone this repository**
   ```bash
   git clone https://github.com/vipunsanjana/MLO-ml-feature-selection-rfe.git
   cd MLO-ml-feature-selection-rfe
   ````

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Explore the Jupyter Notebook**

   ```bash
   jupyter notebook MLO_Feature_Selection_Boston_LinearRegression.ipynb
   ```

---

## 📈 Example Outputs

### 🏡 Boston Housing Prediction

* Fold-wise **RMSE values**
* Average **RMSE** across folds
* Selected important features via **RFE / RFECV**
* Reduced feature dataset for improved efficiency

---

## ✅ Future Improvements

* Add **Ridge** and **Lasso Regression** for regularization and comparison
* Apply **feature scaling** for better performance
* Add **visualizations** (residual plots, feature importance)
* Extend to **Polynomial Regression** for non-linear patterns

---

## 👨‍💻 Author

**Vipun Sanjana**
*Software Engineer | Full Stack | ML & DevOps*

---

