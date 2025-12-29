# 👕 Men’s T-Shirt Sales & Brand Analysis Dashboard (Power BI)

## 🔗 Dashboard Tool
**Microsoft Power BI**

---

## 📌 Problem Statement

The fashion retail industry generates large volumes of sales data across **brands, pricing, discounts, profits, and product varieties**.  
Manually analyzing this data makes it difficult to identify **top-performing brands**, **profitability trends**, and **discount strategies**.

This dashboard provides an **interactive and visual analytics solution** to help:
- Analyze **brand-wise discounts and profits**
- Identify **top and bottom performing brands**
- Understand **pricing and variety distribution**
- Support **business and merchandising decisions**

---

## 📊 Dashboard Preview

### 🔹 Landing Page – Men’s Collection
## 📊 Brand Analysis Dashboard [file:34]

![Landing Page - Men's Collection](https://raw.githubusercontent.com/Pranay25o/Men-s_T-Shirt_Sales_Brand_Analysis/main/Landing%20Page%20%E2%80%93%20Men%E2%80%99s%20Collection.png)

### 🔹 Brand Performance Analysis
## 📊 Brand Analysis Dashboard [file:34]

![Brand Performance Analysis](https://raw.githubusercontent.com/Pranay25o/Men-s_T-Shirt_Sales_Brand_Analysis/main/Brand%20Performance%20Analysis.png)


> 📌 *All images are stored inside the `images/` folder*

---

## 📂 Dataset Description

- **Source:** Retail / Fashion Sales Dataset  
- **Format:** CSV / Excel  
- **Domain:** Retail Analytics / Fashion  

### Key Fields:
- Brand Name  
- Product Category (Men’s T-Shirt)  
- Discount Percentage  
- Profit Percentage  
- Sales Price  
- Number of Varieties  
- Quantity Sold  

---

## 🔄 Data Architecture & Flow

1. **Data Source**
   - Raw sales data (CSV / Excel)

2. **Power BI Desktop**
   - Data imported into Power BI
   - Cleaned and transformed using **Power Query Editor**

3. **Semantic Model**
   - Relationships created
   - Business logic implemented using **DAX measures**

4. **Power BI Report**
   - Interactive dashboards
   - Filters for brand-level analysis

---

## 🧹 Data Cleaning (Power Query)

Data preparation was performed using **Power Query Editor**, including:

- Removed duplicate records  
- Handled missing and null values  
- Standardized brand names  
- Converted numeric columns (price, discount, profit)  
- Validated discount and profit percentages  
- Cleaned inconsistent category values  

---

## 📐 DAX Measures Used

DAX (Data Analysis Expressions) was used to create dynamic calculations:

- Average Discount Percentage  
- Average Profit Percentage  
- Average Sales Price  
- Total Number of Varieties  
- Top 5 Brands by Discount  
- Top 5 Brands by Profit  
- Bottom 5 Brands by Profit  

These measures enable **interactive filtering and comparative analysis**.

---

## 📊 Dashboard Components

### 🔹 Landing Page
- Brand collection showcase
- Available brand list
- Navigation between report pages

---

### 🔹 Brand Performance Analysis

#### 📌 Top 5 Brands by Average Discount %
- Highlights brands offering the highest discounts

#### 📌 Top 5 Brands by Average Profit %
- Identifies the most profitable brands

#### 📌 Top 5 Brands by Highest Number of Varieties
- Shows brands with the widest product range

#### 📌 Top 5 Brands by Average Sales Price
- Compares premium vs budget brands

#### 📌 Bottom 5 Brands by Average Profit %
- Helps identify underperforming brands

---

## 🔧 Steps Followed

1. Imported men’s t-shirt sales dataset into Power BI  
2. Cleaned and transformed data using Power Query  
3. Created DAX measures for discount, profit, and pricing  
4. Designed brand-level comparison visuals  
5. Built Top & Bottom brand analysis charts  
6. Created donut, bar, and line visuals  
7. Applied dark theme for premium UI look  
8. Optimized layout and alignment  
9. Validated insights using filters  

---

## 📈 Key Insights

- Some brands offer high discounts but maintain strong profits  
- A few brands dominate in product variety  
- Premium brands show higher average sales prices  
- Certain brands consistently underperform in profit  
- Discount strategy strongly impacts profitability  

---

## 🛠 Tools & Technologies

- Power BI Desktop  
- Power Query Editor  
- DAX (Data Analysis Expressions)  
- Excel / CSV  

---

## 🚀 Future Enhancements

- Category-wise comparison (shirts, jeans, etc.)  
- Time-based sales trend analysis  
- Profit vs discount correlation analysis  
- Automated data refresh  
- Role-Level Security (RLS)  

---

## 👤 Author

**Pranay Ogale**  
Aspiring Data Analyst | Power BI | SQL | Data Visualization  

🔗 **LinkedIn:** https://www.linkedin.com/in/pranay-ogale/
