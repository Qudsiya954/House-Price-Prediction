# 🏠 Bangalore House Price Prediction App

This project is a web-based application built using **Flask**, **pandas**, and **scikit-learn**. It predicts the price of a house in Bangalore based on user inputs like location, square footage, number of bathrooms, and number of bedrooms (BHK). The machine learning model used is **Ridge Regression**, trained on a cleaned housing dataset.

---

## 🚀 Features

- 🔍 Predicts Bangalore house prices based on:
  - Location
  - Total Square Footage
  - Number of Bathrooms
  - BHK (Bedrooms Hall Kitchen)
- 📊 Machine Learning model trained using Ridge Regression.
- 🌐 User-friendly frontend using HTML & Bootstrap.
- 🧠 Model saved and loaded using `pickle`.
- ✅ Live prediction without page reload using JavaScript (`XMLHttpRequest`).

---

## 🧠 Machine Learning

- **Algorithm Used**: Ridge Regression
- **Libraries**: scikit-learn, pandas, numpy
- **Training**: Performed in Google Colab and saved as `RidgeModel_new.pkl`.
- **Input Features**:
  - `location` (OneHotEncoded)
  - `total_sqft` (float)
  - `bath` (int)
  - `bhk` (int)

---

## 🖼️ Web Interface

- **Backend**: Flask (Python)
- **Frontend**: HTML + Bootstrap
- **Prediction API**: `/predict` route handles POST request and returns the predicted price.

---

## 📦 Installation

1. **Clone this repo**:
   ```bash
   git clone https://github.com/yourusername/house-price-predictor.git
   cd house-price-predictor
   ```
2.**Install dependencies:**
```bash
pip install -r requirements.txt
````
3.***Run the flask App***

---
## Demo Video
A demo video attached in this 


✍️ Author
Qudsiya Siddique
ML enthusiast | Web developer | Python programmer | DL enthusiast



