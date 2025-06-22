<p align="center">
  <img src="https://raw.githubusercontent.com/afzalt3ch/banner.png/main/Gemini_Generated_Image_hb31fqhb31fqhb31.png" alt="WeeBee Banner" width="100%" />
</p>


# 🚗 Car Price Prediction – Machine Learning Project

A machine learning project that predicts the selling price of used cars based on various features such as brand, year, kilometers driven, fuel type, ownership, and transmission type.

---

## 📦 Dataset Overview

The dataset includes 301 records with the following features:

- `Car_Name`: Model of the car  
- `Year`: Manufacturing year  
- `Selling_Price`: Price at which the car is being sold  
- `Present_Price`: Price of the car when new  
- `Driven_kms`: Total kilometers driven  
- `Fuel_Type`: Petrol, Diesel, or CNG  
- `Selling_type`: Individual or Dealer  
- `Transmission`: Manual or Automatic  
- `Owner`: 0 to 3 previous owners

---

## ✅ Project Workflow

1. Data cleaning and outlier removal using the IQR method  
2. Feature engineering: Extracted car age, dropped `Car_Name`  
3. One-hot encoding of categorical columns (`Fuel_Type`, `Transmission`, etc.)  
4. Trained a **Linear Regression** model  
5. Evaluated the model using R² score  
6. Built a prediction function to estimate car price from custom input

---

## 🔍 Key Observations

- Large outliers in `Driven_kms` were removed to improve accuracy  
- Feature correlation showed `Present_Price` and `Year` have the most impact on `Selling_Price`

---


## 📊 Visual Insights

- `Selling_Price` increases with `Present_Price`, especially for newer vehicles  
- Outliers in `Driven_kms` can heavily skew prediction models

### 📷 Sample Visualization

**Selling Price vs Present Price**

![Selling vs Present](https://github.com/afzalt3ch/Car-Price-Prediction/blob/main/screenshots/SellingPrice_VS_PresentPrice.png)

---

## 🛠️ Tech Stack

- `Python`
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## 🚀 Getting Started

```bash
git clone https://github.com/afzalt3ch/Car-Price-Prediction.git
cd Car-Price-Prediction
```
---

## 📊 Model Accuracy

- R² Score on test set: ~57%
- Model: Linear Regression
---

## 📜 License

This project is under the MIT License.

---

<p align="center">Made with ❤️ by <strong>Afzal T3ch</strong></p>

