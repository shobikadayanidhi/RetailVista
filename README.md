# RetailVista
A full-stack solution for retail data analysis, future sales prediction, customer segmentation, and inventory planning.
# 🛍️ RetailVista: Sales Forecasting & Customer Intelligence Dashboard

**RetailVista** is a comprehensive data analytics and machine learning dashboard built on real and synthetic retail data. It’s designed to help businesses like Walmart uncover deep insights from store transactions — forecasting profits, analyzing customer behavior, and optimizing inventory and marketing strategies.

---

## 🚀 Features

✅ Synthetic data generation using Faker for initial simulation  
✅ Exploratory Data Analysis (EDA) with Seaborn & Matplotlib  
✅ Store-wise and product-wise profitability heatmaps  
✅ Sales forecasting using Facebook Prophet  
✅ Customer segmentation with KMeans Clustering  
✅ Outlier detection and distribution visualizations  
✅ Professionally designed Streamlit dashboard (web app ready)

---

## 📁 Project Structure
📦 RetailVista/
├── copy_of_unititled14.py # Main Streamlit dashboard
├── supermarket_sales - Sheet1.csv # Real-world dataset
├── RetailVista-Requirements.txt # Python dependencies
└── README.md # You're here!

---

## 🧠 Key Modules

### 📊 Phase 1: Synthetic Dataset Generation
- Used `Faker` to create a realistic retail dataset with store, product, and sales attributes.

### 🔍 Phase 2: Exploratory Data Analysis
- Cleaned and visualized the dataset to understand patterns in sales, time, and customer behavior.

### 🧱 Phase 3: Feature Engineering
- Extracted `Hour`, `Day`, `Month`, and encoded categorical features to build a powerful model base.

### 📈 Phase 4: Machine Learning Predictions
- **Gross Income Prediction** using Random Forest
- **Customer Segmentation** using KMeans Clustering
- **Sales Forecasting** for each product line using Facebook Prophet

### 📦 Phase 5: Business Intelligence
- Store-level profitability heatmaps
- Product line trend analysis
- Future profit forecast
- Inventory demand forecasting

---

## 🖥️ How to Run the Dashboard

### ▶️ Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
