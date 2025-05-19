# Melbourne Housing Price Forecasting and Emerging Suburb Analysis

This project applies time series forecasting and machine learning to predict housing price growth in Melbourne suburbs and identify areas with the highest growth potential.

## 📊 Project Objective

The aim is to support real estate planning and investment decisions by:
- Forecasting future housing prices by suburb
- Modeling which property features contribute to suburb-level growth
- Ranking the most promising emerging suburbs based on predicted growth

---

## 🔧 Techniques Used

- 🧹 **Data Cleaning & Preprocessing**
  - Removed missing values
  - Date formatting and monthly aggregation
  - Log transformation of skewed features

- 📈 **Time Series Forecasting**
  - Used **Exponential Smoothing (ETS)** per suburb to predict average price trends

- 🤖 **Supervised Learning**
  - Applied **Random Forest Regression** to predict forecasted price growth using features like rooms, land size, distance from CBD, etc.
  - Evaluated model performance using R² and RMSE

- 📉 **Model Evaluation**
  - Train R²: 0.83
  - Test R²: 0.06 → Identified potential overfitting, room for improvement

---

## 📍 Key Findings

- **Top Emerging Suburbs** (predicted highest growth):
  - Balwyn North
  - Bentleigh East
  - Glenroy
  - Pascoe Vale
  - South Yarra

- **Most Influential Features**:
  - Log-transformed land size and building area
  - Property count in the suburb
  - Distance to CBD and number of rooms

---

## 📁 Dataset

- **Source:** Melbourne Housing Market dataset (public)
- **Attributes:** Suburb, Date, Price, Rooms, Bathroom, Car spaces, Landsize, BuildingArea, Distance, Property Count, etc.

---

## 🛠 Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- Statsmodels
- Google Colab

---

## 📌 Future Improvements

- Use **cross-validation** for more robust evaluation
- Tune hyperparameters of Random Forest
- Explore external features like infrastructure, school zones
- Try simpler or regularized models (e.g., Ridge regression)

---

## 📄 Report

> A detailed business analysis report is included in the repository: `Shreeyans Karki Individual Report.pdf`

---

## 👤 Author

**Shreeyans Karki**  
Aspiring Data Scientist | Melbourne, Australia  
[LinkedIn](https://www.linkedin.com/) | [GitHub](https://github.com/yourusername)  
