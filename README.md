# 📊 Online Retail Data Visualization

**CodeAlpha Data Science Internship — Task 3**

**Author:** Uzair Khan  
**Date:** 5 April 2026  

---

## 📑 Table of Contents

1. Project Overview  
2. Dataset  
3. Tech Stack  
4. Project Structure  
5. Setup & Installation  
6. Data Cleaning  
7. Visualizations  
8. Key Findings  
9. Recommendations  
10. License  

---

## 📌 Project Overview

This project performs  **Data Visualization** on an online retail dataset containing more than **536,000 transactions** from a UK-based online retailer.

### Objective
Transform raw transaction data into meaningful visual insights that support **business decision-making**.

### Scope
- Data cleaning and preprocessing  
- Revenue trend analysis  
- Country-wise sales distribution  
- Top selling products  
- Correlation analysis between variables  

---

## 📂 Dataset

| Attribute | Information |
|-----------|-------------|
| Source | UCI Machine Learning Repository |
| Records | 536,641 transactions |
| Countries | 38 |
| Time Period | December 2010 – December 2011 |

### Dataset Features

| Column | Description |
|------|-------------|
| InvoiceNo | Unique invoice number |
| StockCode | Product code |
| Description | Product name |
| Quantity | Units purchased |
| InvoiceDate | Transaction date |
| UnitPrice | Price per unit (£) |
| CustomerID | Unique customer ID |
| Country | Customer country |

---

## 🛠 Tech Stack

| Tool | Purpose |
|-----|--------|
| Python | Data analysis |
| Pandas | Data cleaning & transformation |
| Matplotlib | Charts and graphs |
| Seaborn | Statistical visualization |
| OpenPyXL | Reading Excel files |
| Google Colab | Development environment |

---

## 📁 Project Structure

```
CodeAlpha_Data_Visualization/
│
├── Final_Analysis_Report by Uzair_Khan.pdf   # Final analysis report with insights
├── Final_data set.xlsx                       # Cleaned dataset used for visualization
├── Original_data set.xlsx                    # Raw dataset before cleaning
├── codealpha task3 code.py.pdf               # Python code used for data visualization
├── README.md                                 # Project documentation
└── LICENSE                                   # MIT License
```

---

## ⚙️ Setup & Installation

### Step 1 – Clone Repository

```
git clone https://github.com/UzairKhan/CodeAlpha-Task3-Data-Visualization.git
cd CodeAlpha-Task3-Data-Visualization
```

### Step 2 – Install Required Libraries

```
pip install pandas matplotlib seaborn openpyxl
```

### Step 3 – Run the Notebook

Open **Untitled8.ipynb** in **Jupyter Notebook** or upload it to **Google Colab**, then run all cells.

---

## 🧹 Data Cleaning

The following preprocessing steps were applied:

- Removed rows with missing values  
- Removed negative quantities (returns)  
- Created a new **TotalPrice** column  
- Converted **InvoiceDate** to datetime format  
- Extracted month for monthly analysis  

---

## 📊 Visualizations

### Top Countries by Revenue
**Chart:** Bar Chart  

**Insight:**  
The **United Kingdom generates around 90% of total revenue**, with other countries contributing significantly less.

---

### Monthly Sales Trend
**Chart:** Line Chart  

**Insight:**  
Revenue peaks in **November** due to holiday demand and is lowest in **February**.

---

### Top Selling Products
**Chart:** Bar Chart  

**Insight:**  
Most top-selling products belong to the **home decor and giftware categories**.

---

### Correlation Matrix
**Chart:** Heatmap  

| Variables | Correlation |
|----------|-------------|
| Quantity vs TotalPrice | 0.91 (Strong) |
| UnitPrice vs TotalPrice | 0.08 (Weak) |
| UnitPrice vs Quantity | ≈0 (None) |

**Insight:**  
Revenue growth is mainly driven by **sales volume rather than price increases**.

---

## 🔍 Key Findings

- **Revenue Concentration:** Around 90% of revenue comes from the UK.  
- **Seasonal Demand:** Sales increase significantly in Q4 (holiday season).  
- **Product Category Focus:** Top-selling products are mostly gift and decor items.  
- **Volume-Driven Revenue:** Higher quantities sold strongly increase revenue.  
- **Customer Data Gap:** Around 25% of records lack CustomerID.

---

## 💡 Recommendations

| Priority | Recommendation |
|--------|----------------|
| High | Prepare inventory for Q4 demand surge |
| High | Improve CustomerID data collection |
| Medium | Expand marketing in Netherlands, Germany, and France |
| Medium | Run promotions during low-demand months |
| Low | Analyze product returns separately |

---

## 📜 License

This project was completed as part of the **CodeAlpha Data Analysis Internship Program** and is intended for **educational and portfolio purposes**.

---

⭐ If you found this project useful, consider giving it a star on GitHub!
