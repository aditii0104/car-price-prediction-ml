# 🚗 Car Price Prediction

## 📌 Project Overview

This project focuses on **predicting car prices** using historical automobile data. It includes **exploratory data analysis (EDA)**, **data preprocessing**, and **feature encoding** to prepare the dataset for machine learning models.
The goal is to understand the factors influencing car prices and build a clean, model-ready dataset.
---

## 🧠 Key Objectives

* Analyze the relationship between car features and price
* Visualize data trends and correlations
* Handle categorical variables using encoding techniques
* Prepare data for machine learning models
---

## 📂 Dataset Features

The dataset contains the following key attributes:

* `price` – Target variable
* `year` – Manufacturing year
* `mileage` – Distance driven
* `model` – Car model
* `transmission` – Manual / Automatic
* `fuelType` – Petrol / Diesel / Hybrid / Electric
---

## 🔍 Exploratory Data Analysis (EDA)

The following visualizations were performed:

* **Distribution of car prices** using histogram
* **Correlation heatmap** for numerical features
* **Boxplots** for price vs year
* **Scatter plots** for mileage vs price
* **Fuel type vs price analysis** using boxen plots

Libraries used for EDA:

* `matplotlib`
* `seaborn`
---

## 🛠 Data Preprocessing

* Checked for missing values
* Separated features (`X`) and target variable (`y`)
* Applied **One-Hot Encoding** to categorical variables:

  * `model`
  * `transmission`
  * `fuelType`
* Converted encoded features to integer type

```python
pd.get_dummies(columns=['model','transmission','fuelType'], drop_first=True)
```

---

## ⚙️ Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
---

## 🚀 Future Enhancements

* Implement regression models (Linear, Random Forest, XGBoost)
* Perform feature scaling using `StandardScaler`
* Evaluate models using R² and RMSE
* Deploy using Flask or Streamlit
---

## ▶️ How to Run

1. Clone the repository
2. Install required libraries
3. Open the Jupyter Notebook
4. Run cells sequentially

