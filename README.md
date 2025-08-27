
# 🏡 Bangalore House Price Prediction

## 📌 Overview

This project focuses on predicting house prices in Bangalore using **Machine Learning models**.
We clean, preprocess, and engineer features from the dataset, remove outliers, and train multiple models to select the best one using **GridSearchCV**.

---

## 📂 Project Structure

```
├── data/                     # Dataset files
├── notebooks/                # Jupyter notebooks
│   └── house_price.ipynb     # Main notebook with EDA & modeling
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies
```

---

## 🔑 Key Steps

1. **Data Preprocessing**

   * Handle missing values
   * Feature engineering: price per square foot
   * Group rare locations under "other"
   * Convert categorical variables using one-hot encoding

2. **Outlier Removal**

   * Removed extreme values based on price per square foot
   * Handled outliers across BHK and location

3. **Modeling**

   * Models tested:

     * **Linear Regression**
     * **Lasso Regression**
     * **Decision Tree Regressor**
   * Used **GridSearchCV + ShuffleSplit** for hyperparameter tuning

4. **Results**

   * **Linear Regression** performed best (highest cross-validation score).
   * Lasso helped with feature selection but was less accurate.
   * Decision Tree overfitted on training data.

---

## 📊 Technologies Used

* **Python**
* **Pandas, NumPy** – Data handling
* **Matplotlib, Seaborn** – Visualization
* **Scikit-learn** – Machine learning models & evaluation

---

## 🚀 Conclusion

* **Linear Regression** was selected as the final model.
* The model can predict Bangalore house prices with good generalization performance.
* This pipeline can be extended to other cities with minimal modifications.

---

## 📎 Links

* 📘 [Dataset Source](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)
* 💻 [GitHub Repository](https://github.com/kavya181205/house-price-prediction) *(replace with your repo link)*

---

👉 Do you also want me to include a **"How to Run" section** with installation and execution commands (so others can easily test your notebook)?
