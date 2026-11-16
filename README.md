# 🛒 E-Commerce Sales & Customer Behaviour Analytics

**Capstone Project #2 | BCA – Artificial Intelligence & Data Science**

An exploratory data analysis project that examines e-commerce sales trends, product categories, customer behaviour and regional performance using Python. The project also includes an interactive Plotly dashboard.

---

## 📌 Project Overview

This project analyses a synthetic e-commerce dataset containing **60 orders from 2025** to understand the factors influencing sales and customer purchasing behaviour.

The main business question is:

> Which categories, customers, regions and months drive revenue, and does product price affect how much customers buy?

## 🎯 Objectives

- Inspect and understand the dataset.
- Perform exploratory data analysis (EDA).
- Analyse relationships using correlation.
- Compare sales using Pandas `groupby()`.
- Create visualisations using Matplotlib.
- Build an interactive dashboard using Plotly.
- Export the dashboard as an HTML file.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Dataset generation |
| Matplotlib | Static visualisations |
| Plotly | Interactive dashboard |
| Google Colab | Notebook execution |

## 📂 Project Structure

```text
ecommerce-sales-analytics/
│
├── ecommerce_dashboard.ipynb
├── ecommerce_dashboard.html
├── ecommerce_sales.csv
├── Ecommerce_Capstone_Report_Sambhav_Chauhan.pdf
└── README.md
```

## 📊 Dataset

- **Records:** 60 orders
- **Columns:** 13
- **Period:** January–December 2025
- **Currency:** Indian Rupees (₹)
- **Data type:** Synthetic sample dataset

The dataset includes order dates, customer types, product categories, product prices, quantities, discounts, sales, regions and payment methods.

## 🔍 Key Findings

| Metric | Result |
|---|---:|
| Total Sales | ₹2,88,702 |
| Average Order Value | ₹4,811.70 |
| Highest Sales Month | November |
| Leading Category | Fashion |
| Top Region | East |
| Returning Customer Revenue Share | 59% |

### Important Insights

1. **Seasonal Sales:** The fourth quarter (October–December) contributes approximately 46% of annual revenue.
2. **Category Performance:** Fashion generates the highest revenue, followed by Electronics.
3. **Customer Behaviour:** Returning customers contribute approximately 59% of total sales.
4. **Regional Performance:** The East region records the highest sales.
5. **Price and Quantity:** Product price and quantity have a moderate negative correlation (r = -0.40).

## 📈 Visualisations

The project includes:

- Monthly sales trend analysis.
- Revenue comparison by product category.
- Product price versus quantity analysis.
- Customer type revenue contribution.
- Regional sales comparison.

The interactive Plotly dashboard provides hover details and interactive chart controls.

## 🚀 How to Run

### Option 1: Google Colab

1. Download or open `ecommerce_dashboard.ipynb`.
2. Upload it to Google Colab.
3. Run the notebook cells in sequence.
4. The notebook generates the dataset and exports the interactive dashboard.

### Option 2: Local Environment

Install the required libraries:

```bash
pip install pandas numpy matplotlib plotly jupyter
```

Open the notebook:

```bash
jupyter notebook ecommerce_dashboard.ipynb
```

Run the cells in order.

## 🌐 Interactive Dashboard

Open `ecommerce_dashboard.html` in a web browser to explore the interactive dashboard.

**Note:** An internet connection is required because the exported HTML loads the Plotly JavaScript library from a CDN.

## 📄 Project Report

The complete project report is available here:

`Ecommerce_Capstone_Report_Sambhav_Chauhan.pdf`

## 📝 Reflection

This project provided practical experience in data inspection, exploratory data analysis, correlation, aggregation and data visualisation. It demonstrated how sales data can be transformed into meaningful insights through Python and interactive dashboards.

The dataset is synthetic and relatively small, so the findings are illustrative rather than representative of an actual e-commerce business.

---

**Created by:** Sambhav Chauhan  
**Roll Number:** 2601060237  
**Programme:** BCA – Artificial Intelligence & Data Science
