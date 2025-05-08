# 🧐 Dominos | Predictive Purchase Order System

**Data Science Project | Food Service Industry | Inventory Forecasting**

---

## 📌 Summary

This end-to-end project builds a **predictive system to optimize ingredient ordering** for Domino's using advanced **time series forecasting techniques**. By integrating historical sales data with ingredient mapping, we generate **data-driven purchase orders** to reduce waste, ensure supply continuity, and support demand planning.

As a **Data Scientist**, I led the **design, modeling, and implementation** of this system, leveraging real-world techniques and frameworks that mirror production-level forecasting.

---

## 🌟 Project Objectives

1. **Forecast pizza sales** for the next week.
2. **Translate sales forecasts** into ingredient requirements.
3. **Automate purchase order generation** using predicted ingredient needs.
4. Deliver a reproducible, interpretable, and business-aligned solution.

---

## 🔍 Problem Statement

> Dominos needs a system that anticipates weekly pizza demand and dynamically creates a purchase order for ingredients. This reduces operational inefficiencies due to over-ordering or under-ordering ingredients.

---

## 🧪 Solution Workflow

```mermaid
graph TD;
    A[Data Collection] --> B[Data Cleaning & Exploration];
    B --> C[Feature Engineering];
    C --> D[Model Selection: SARIMA, Prophet];
    D --> E[Model Training & Forecasting];
    E --> F[Ingredient Quantification];
    F --> G[Purchase Order Generation];
    G --> H[Business Insights & Visualization];
```

---

## 🛠️ Tools & Technologies

* **Languages**: Python (v3.10+)
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **Time Series**: ARIMA, SARIMA (Pmdarima), Prophet (Meta), LSTM (Keras),Regression
* **Evaluation**: Mean Absolute Percentage Error (MAPE)
* **Environment**: Jupyter Notebook, GitHub

---

## 📈 Modeling Highlights

### 🔹 Forecasting Algorithms Used:

* **SARIMA**: Seasonal AutoRegressive Integrated Moving Average
* **ARIMA**:  AutoRegressive Integrated Moving Average
* **Prophet**: Decomposable time series model by Meta
* **LSTM**: Long Short Term Memory
* **Regression**: Linear model for forecasting based on historical sales trends.

### 🔹 Feature Engineering:

* Day-of-week effects
* Monthly/seasonal trends
* Holidays and promotional flags

### 🔹 Performance Metric:

* **MAPE** (Mean Absolute Percentage Error)

---

## 📊 Key Results

* Achieved **<10% MAPE** on validation data
* Forecasted weekly pizza sales with high accuracy
* Mapped predicted sales to ingredient needs
* Generated a **structured purchase order** with total quantities per ingredient

---

## 📂 Datasets

* `sales_data.csv` – Historical pizza sales (date, quantity, pizza type, category, price)
* `ingredients_data.csv` – Pizza-to-ingredient mappings with required gram quantities

---

## 🚀 How to Run

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/dominos-predictive-purchase-order.git
cd dominos-predictive-purchase-order
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run notebooks**
   Open JupyterLab or VSCode and run the scripts in order:

* `01_cleaning_exploration.ipynb`
* `02_forecasting_models.ipynb`
* `03_purchase_order.ipynb`

---

## 📚 Learnings & Takeaways

* Applied **SARIMA and Prophet** for real-world demand forecasting
* Gained experience in **ingredient-level demand translation**
* Strengthened understanding of **business-aligned modeling**
* Built a modular, reusable project pipeline suitable for enterprise use

---

## 👨‍💻 Author

**\[Your Full Name]**
Data Scientist | Machine Learning Enthusiast
📧 [your.email@example.com](mailto:your.email@example.com)
🔗 [LinkedIn](https://www.linkedin.com/in/yourname) | 💻 [GitHub](https://github.com/yourusername)

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

## 🙌 Acknowledgements

* Meta for Prophet
* Statsmodels & Pmdarima for ARIMA/SARIMA
* Dominos sales dataset (mock/demo-based)

