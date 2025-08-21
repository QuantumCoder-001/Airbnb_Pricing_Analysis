# 🏠 Airbnb Dynamic Pricing Dashboard  

[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue?logo=python)](https://www.python.org/)  
[![Tableau](https://img.shields.io/badge/Visualization-Tableau-orange?logo=tableau)](https://www.tableau.com/)  
[![Machine Learning](https://img.shields.io/badge/ML-Random%20Forest-green?logo=scikit-learn)](https://scikit-learn.org/)  

> 📊 **An interactive pricing optimization tool for Airbnb hosts**  
> Combines **machine learning** (price prediction) with **Tableau dashboards** (dynamic insights) to make smarter revenue decisions.  

---

## 🚀 Overview  
This project builds a **dynamic pricing solution** for Airbnb listings by:  
- Training a **Random Forest Regression model** on listing features  
- Predicting optimal listing prices  
- Allowing hosts to test different **price adjustment scenarios**  
- Visualizing results with a **Tableau dashboard**  

✨ The aim: **maximize revenue while staying competitive**.  

---

## ⚙️ Tech Stack  
| Tool | Purpose |
|------|----------|
| 🐍 Python | Data cleaning, ML model training |
| 📊 Tableau | Interactive dashboards & filters |
| 📦 Scikit-learn | Random Forest Regression |
| 📑 Pandas, NumPy | Data wrangling & preprocessing |
| 📉 Matplotlib, Seaborn | Exploratory Data Analysis |

---

## 📈 Features  
✅ Predicts prices using ML (R² ~0.49)  
✅ Compares **Predicted vs Adjusted** prices  
✅ Interactive filters: neighborhood, room type, availability  
✅ Parameter control: **Price Adjustment (%)**  
✅ Dashboard with **neighborhood insights + bar comparisons**  

---

## 📊 Dashboard Preview  
🔹 **Sheet 1** → Average neighborhood prices (Highlights vs Unknown)  
🔹 **Sheet 2** → Predicted vs Adjusted prices (interactive)  

*(👉 Add screenshots here once you export from Tableau)*  

---

## 🛠️ How to Use  

### 1. Clone Repository  
```bash
git clone https://github.com/yourusername/airbnb-dynamic-pricing.git
cd airbnb-dynamic-pricing
