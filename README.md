# Car-Price-Prediction-Dashboard-ML-Streamlit-A-premium
Interactive dashboard that predicts used car prices using a Multiple Linear Regression (MLR) model. Includes a luxury-themed UI, animated components, real-time gauge visualizations, dynamic charts, and theme customization options (Gold / Dark / Neon). Built with Python, Streamlit, Plotly, NumPy, Pandas and Scikit-Learn.

# 🚗 Car Price Prediction Dashboard  
### A Machine Learning + Streamlit Based Interactive Analytics App  

This project predicts the **selling price of a used car** using a **Multiple Linear Regression (MLR)** model and visualizes the results through a premium, animated, and theme-customizable Streamlit interface.

---

## ⭐ Features

### 🔮 **Machine Learning**
- Multiple Linear Regression model  
- One-hot encoding for categorical variables  
- Predicts price using key features:
  - Vehicle age  
  - Kilometers driven  
  - Mileage  
  - Engine CC  
  - Max power  
  - Seats  
  - Fuel type  
  - Seller type  
  - Transmission mode  

### 🖥️ **Interactive Streamlit UI**
- Luxury gold theme (default) + Dark + Neon themes  
- Gapless, polished **Home Page** with animated cards  
- **Predict Page** with:
  - Real-time gauge meter  
  - Dynamic car image preview  
  - Smooth animated prediction reveal  
- **Visuals Page**:
  - Engine vs Price  
  - Mileage vs Price  
  - Distribution plots  
  - Numeric-only correlation heatmap  
- **Settings Page**:
  - Theme changer  
  - About App  
  - About Developer  
  - Version information  

---

## 📊 Model Overview
The app uses a **Multiple Linear Regression** model:

\[
\text{Price} = b_0 + \sum (b_i \times X_i)
\]

- Coefficients show how each feature influences the final price.  
- The model is saved as `priceprediction.pkl` for real-time inference.

---

## 🛠️ Tech Stack
- **Python**  
- **Streamlit**  
- **Pandas, NumPy**  
- **Plotly, Seaborn, Matplotlib**  
- **Scikit-Learn (MLR)**  

---

## 📁 Repository Structure

