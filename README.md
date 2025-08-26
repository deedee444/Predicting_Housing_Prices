## 🧠 Problem Statement

Predict the **SalePrice** of a house given a variety of features, including physical attributes and location. The dataset contains both numerical and categorical variables, and some missing data.

---

## 📊 Dataset

- **Source:** [Kaggle House Prices Competition](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)
- **Size:** 1460 training examples, 81 features
- **Target variable:** `SalePrice` (continuous)

---

## 🧰 Tools & Technologies

- Python 3.9+
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

---

## ⚙️ Modeling Approach

The following regression model was explored:

- 🔹 **Lasso Regression**


**Model Evaluation Metrics:**
- Mean Squared Error (RMSE)


---

## 📈 Results


Id	SalePrice
0	1461	118697.778232
1	1462	160273.563883
2	1463	185765.094054
3	1464	199111.771806
4	1465	209609.223206



---

## 🔍 Key Insights

- Regularization (Lasso) helps manage multicollinearity and overfitting.
- Feature scaling and encoding significantly impact performance.

---

## 🚀 How to Run This Project

1. Clone the repository:
   ```bash
   git clone https://github.com/deedee444/house-price-prediction.git
   cd house-price-prediction
2. Download the dataset from kaggle in the following url: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/

3. Save the Data inside the house-price-prediction folder in a subfolder named Data

3. in bash
	- jupyter Lasso_Reg.ipynb
