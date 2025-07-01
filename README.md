**# Superstore Sales Forecasting and Insights (2014–2018)**

This project demonstrates a complete end-to-end sales analysis and time series forecasting workflow using Python and Tableau, based on a retail Superstore dataset. It includes data cleaning, exploratory data analysis (EDA), SARIMA modeling, and interactive data storytelling using Tableau Public.

---

## 📅 Project Duration

**1 Juky 2025**

---

## 📊 Objective

To analyze historical retail sales data and develop a predictive model for future sales using time series forecasting, while visualizing the insights for strategic decision-making.

---

## 📁 Dataset

* **Source:** https://www.kaggle.com/datasets/vivek468/superstore-dataset-final?resource=download
* **Timeframe:** January 2014 – December 2017
* **Features:**

  * Order ID, Order Date, Ship Date
  * Sales, Profit, Quantity, Discount
  * Customer Segment, Region, Category, Sub-category, Product Name

---

## ⚖️ Tools & Technologies

* **Python (Pandas, NumPy, Matplotlib, Seaborn, Statsmodels)**
* **Jupyter Notebook**
* **Tableau Public**

---

## 🔍 Key Steps & Methods

### 1. Data Cleaning

* Converted `Order Date` and `Ship Date` to datetime
* Removed duplicates
* Checked for null values

### 2. Exploratory Data Analysis (EDA)

* Top 5 best-selling products
* Sales by Category and Sub-category
* Sales and profit breakdown by Region
* Daily sales and profit trends (2014-2017)

### 3. Time Series Forecasting (SARIMA)

* Aggregated sales monthly
* Checked for stationarity using the Augmented Dickey-Fuller(ADF) test
* Built multiple models:

  * ARIMA(1,1,1)
  * SARIMA(1,1,1)(1,1,1,12)
* SARIMA outperformed ARIMA in AIC/BIC and residual diagnostics
* Forecasted monthly sales from Jan to Jun 2018

### 4. Visualization in Tableau

* Created line chart showing:
  * Monthly forecast
  * Confidence intervals (upper/lower bounds)
* Created interactive dashboard
* Built a 3-point Tableau Story with insights and recommendations

---

## 🌍 Tableau Public Links

* 🔺 **Dashboard:** https://public.tableau.com/app/profile/bheki.mogola/viz/Superstoresalesforecastandperfomance/SalesForecastDashboard-Superstore2014-2018#1
* 📖 **Story:** https://public.tableau.com/app/profile/bheki.mogola/viz/Superstoresalesforecastandperfomance/Monthlysalesforecaststorypresentation#1

---

## 📈 Key Insights

* **Sales Trends:** Peaks occur towards end of each year; dips in Jan/Feb.
* **Top Products:** Canon Copiers and Cisco TelePresence Systems lead in sales.
* **Top Regions:** West and East regions have the highest sales and profits.
* **Forecast:** Predicted sales stabilize between R72,000 – R75,000 from Jan–Jun 2018.
* **SARIMA diagnostics** showed no autocorrelation in residuals, constant variance, and normal distribution.

---

## 💡 Business Recommendations

* Prepare inventory for low-demand periods early in the year
* Target promotions around mid-year and Q4
* Reassess forecasts monthly with new data
* Focus on top-performing categories and customer segments

---

## 💼 Author

**Bheki Mogola**
Aspiring Data Analyst | Python & Tableau | GenAI Enthusiast
[LinkedIn](https://www.linkedin.com/in/bheki-mogola-8481122b7) | [bpmogola@gmail.com](mailto:bpmogola@gmail.com)

---

## ℹ️ License

This project is licensed under the [MIT License](LICENSE).


