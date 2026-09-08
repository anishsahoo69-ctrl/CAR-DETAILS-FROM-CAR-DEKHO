# CAR-DETAILS-FROM-CAR-DEKHO
# 🚗 Used Car Price Prediction & Analysis

An Exploratory Data Analysis (EDA) and Machine Learning project analyzing used car sales data from **CarDekho**. This repository inspects car specifications, ownership details, transmission types, fuel preferences, and pricing distributions to uncover key trends in the second-hand automobile market.

---

## 📌 Project Overview

Understanding the factors that influence the resale value of used cars is essential for buyers, sellers, and dealerships. This project explores a dataset of used cars to identify patterns related to:
* **Selling Price Distribution & Outliers**
* **Vehicle Age & Mileage (`km_driven`) Impact**
* **Transmission & Fuel Type Preferences**
* **Ownership History Trends**

---

## 📊 Dataset Summary

* **Source:** CarDekho Used Car Details
* **Total Records:** 4,340 entries
* **Total Features:** 7 key variables + Vehicle Name (`name` as index)

### Feature Description

| Column | Data Type | Description |
| :--- | :--- | :--- |
| **`name`** | Categorical | Brand and model name of the car |
| **`year`** | Integer | Manufacturing year |
| **`selling_price`** | Integer | Resale price of the car (in ₹) |
| **`km_driven`** | Integer | Total kilometers driven |
| **`fuel`** | Categorical | Fuel type (*Petrol, Diesel, CNG, LPG, Electric*) |
| **`seller_type`** | Categorical | Seller category (*Individual, Dealer, Trustmark Dealer*) |
| **`transmission`** | Categorical | Gearbox type (*Manual, Automatic*) |
| **`owner`** | Categorical | Ownership history (*First, Second, Third, etc.*) |

---

## 🛠️ Tech Stack & Libraries

* **Language:** Python 3.x
* **Data Analysis:** `pandas`, `numpy`
* **Visualization:** `seaborn`, `matplotlib`
* **Environment:** Jupyter Notebook / Google Colab

---
