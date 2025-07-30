# 📊 Lookalike Model - Sales Data Analysis Project

## 🔍 Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on customer, product, and transaction data. The goal is to extract valuable insights such as top-selling products, high-value customers, regional performance, category trends, and time-based sales patterns.

## 🧾 Datasets Used

The project includes the following CSV files:

- `Customers.csv`: Customer demographic and signup information.
- `Products.csv`: Product catalog including category and pricing.
- `Transactions.csv`: Sales transaction details including quantity, value, and timestamp.

## 📁 Files in the Project

| File Name         | Description                                                                 |
|------------------|-----------------------------------------------------------------------------|
| `Lookalike_Model_EDA.ipynb` | Jupyter Notebook containing all analysis code, visualizations, and comments. |
| `Customers.csv`   | Contains 200 records of customer information.                             |
| `Products.csv`    | Includes 100 products with prices and categories.                         |
| `Transactions.csv`| Comprises 1000 transaction logs.                                          |
| `README.md`       | You're reading it! Project documentation and usage overview.              |

## 📊 Key Steps in the Analysis

### 1. 📥 Data Loading & Preprocessing
- Loaded datasets using `pandas`.
- Checked and confirmed no missing/null values.
- Converted date columns to proper `datetime` format.

### 2. 🔎 Exploratory Data Analysis (EDA)
- Merged datasets using `CustomerID` and `ProductID`.
- Examined product pricing (min, max, average).
- Verified the date range of transactions.

### 3. 📈 Insights Extracted
- **Top 10 Products by Revenue**
- **Top 10 High-Value Customers**
- **Region-wise Sales Summary**
- **Category-wise Sales Summary**
- **Correlation Matrix** between Quantity, Price, and Total Sales
- **Sales Heatmaps** using:
  - Weekly Trends
  - Monthly Trends
  - Quarterly Trends
- **Cross-tab Analysis** for Region vs Category-wise performance

### 4. 📅 Time Series Analysis
- Weekly, monthly, and quarterly resampling using `resample()`.
- Trend lines and bar plots created using `seaborn` and `matplotlib`.

## 📊 Visualizations

The project includes over 10 different charts and tables:
- Region-wise and Category-wise performance
- Time series plots for monthly and weekly sales
- Annotated bar plots for detailed numeric insights
- Correlation heatmap and tabular views

## 🛠 Tools & Libraries

- Python 3.x
- Jupyter Notebook
- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`

## ✅ Key Findings

- **South America** leads in total revenue and quantity sold.
- **Books** are the highest-selling product category.
- **Quarter 3 of 2024** saw the highest revenue among all quarters.
- Positive correlation between `Price` and `TotalValue`.

---

## 📂 Folder Structure

```

📁 Lookalike\_Model\_Sales\_Analysis
│
├── Lookalike\_Model\_EDA.ipynb
├── Customers.csv
├── Products.csv
├── Transactions.csv
└── README.md

```

---

## 🧠 Future Scope

- Customer segmentation using clustering (K-Means, DBSCAN)
- Market Basket Analysis using Apriori or FP-Growth
- Predictive modeling for customer lifetime value (CLV)

---

## 📬 Contact

Feel free to connect if you have questions or want to collaborate!
