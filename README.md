# 🛍️ Online Retail Sales - Exploratory Data Analysis (EDA) Project

## 📌 Project Overview

This project involves performing **Exploratory Data Analysis (EDA)** on a real-world e-commerce dataset to uncover key business insights. The objective is to analyze customer purchasing behavior, identify top-selling products, discover seasonal trends, and segment customers using RFM analysis.

The project uses Python for data cleaning, visualization, and analysis, and Power BI for creating an interactive dashboard that highlights insights.

---

## 📁 Dataset Information

- **Source**: [Kaggle – Online Retail Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/online-retail-dataset)
- **Duration**: December 2010 – December 2011
- **Records**: ~500,000
- **Features**:
  - `InvoiceNo`: Unique invoice number
  - `StockCode`: Product/item code
  - `Description`: Product name
  - `Quantity`: Number of products purchased
  - `InvoiceDate`: Date and time of purchase
  - `UnitPrice`: Price per product
  - `CustomerID`: Unique ID assigned to each customer
  - `Country`: Customer's country

---

## 🎯 Project Goals

- Clean and preprocess the dataset
- Perform univariate, bivariate, and multivariate analysis
- Discover patterns in customer and product behavior
- Segment customers using RFM (Recency, Frequency, Monetary) analysis
- Build a Power BI dashboard to visualize findings

---

## 🔍 Exploratory Data Analysis (EDA)

### 🧼 Data Cleaning:
- Handled missing values (e.g., `CustomerID`, `Description`)
- Removed duplicates and canceled orders (InvoiceNo starting with ‘C’)
- Removed or capped outliers in `Quantity` and `UnitPrice`
- Converted `InvoiceDate` to datetime format

### 📊 Analysis Performed:

#### General Overview:
- Unique products, transactions, and customers
- Countries represented in the dataset

#### Product Analysis:
- Top 10 products by quantity sold
- Top 10 revenue-generating products
- Products with zero or negative unit prices

#### Customer Analysis:
- Customers who bought the most
- Distribution of purchases
- Loyal customer identification

#### Time Series & Trends:
- Monthly sales trends
- Weekly transaction patterns
- Peak sales periods

#### Country-wise Analysis:
- Orders and revenue comparison by country

#### RFM Segmentation:
- Recency: Days since last purchase
- Frequency: Number of purchases
- Monetary: Total spending
- Used to identify loyal and high-value customers

---

## 📊 Power BI Dashboard

The project includes an interactive Power BI dashboard with the following pages:

### 1. Sales Overview
- KPIs: Total Revenue, Total Invoices, Total Customers
- Monthly sales trend (Line Chart)

### 2. Top Products
- Top 10 by quantity and revenue (Bar Charts)
- Product breakdown (Pie or Treemap)

### 3. Customer Segments
- RFM segmentation (Scatter Plot + Table)
- Top 10 loyal customers

### 4. Geographical Insights
- Sales by country (Map & Bar Chart)

---

## 🛠️ Tools & Technologies

- **Python**: pandas, numpy, matplotlib, seaborn, openpyxl
- **Jupyter Notebook**: for EDA
- **Power BI Desktop**: for dashboard creation
- **Kaggle**: for dataset access

---

## 📁 Project Structure

```

Online-Retail-Sales-EDA/
├── data/
│   └── OnlineRetail.csv
├── notebook/
│   └── online\_retail\_eda.ipynb
├── dashboard/
│   └── Online\_Retail\_Sales\_Dashboard.pbix
├── requirements.txt
└── README.md

````

---

## 💻 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/HafsaNoorMuhammad26/Online-Retail-Sales-EDA.git
cd Online-Retail-Sales-EDA
````

### 2. Install required dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the EDA notebook

Open `notebook/online_retail_eda.ipynb` in Jupyter Notebook or JupyterLab and execute the cells step-by-step.

### 4. Open the Power BI dashboard

Open `dashboard/Online_Retail_Sales_Dashboard.pbix` using Power BI Desktop to explore the interactive visualizations.

---

## 📌 Key Takeaways

* Real-world data often contains missing values, duplicates, and outliers that must be handled before analysis
* Visualizations are crucial in storytelling and revealing insights
* RFM analysis is a powerful method for customer segmentation
* Power BI helps convert raw analysis into easy-to-consume dashboards

---

## 🙋‍♀️ Author

**Hafsa Noor Muhammad**
🔗 [LinkedIn](https://www.linkedin.com/in/hafsa-noor-muhammad-67b96331a/)

---

⭐ *If you found this project helpful, feel free to star the repo and share it with others!*

```
