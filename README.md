# Online Retail Data Analysis

## 📌 Project Overview
This project analyzes an **Online Retail Dataset** to gain insights into customer behavior, sales trends, and product performance. The analysis includes **data cleaning, exploratory data analysis (EDA), feature engineering, and customer segmentation (RFM Analysis)** using **Python, Pandas, Matplotlib, and NumPy**.

## 📂 Dataset Information
- **Source**: UCI Machine Learning Repository
- **File**: `Online Retail.xlsx`
- **Attributes**:
  - `InvoiceNo`: Unique transaction ID
  - `StockCode`: Product identifier
  - `Description`: Product name
  - `Quantity`: Number of products sold
  - `InvoiceDate`: Transaction date
  - `UnitPrice`: Price per unit
  - `CustomerID`: Unique customer identifier
  - `Country`: Country of transaction

## 📊 Analysis Performed
1. **Data Cleaning**:
   - Handling missing values
   - Removing invalid transactions
2. **Exploratory Data Analysis (EDA)**:
   - Monthly sales trends
   - Top 5 countries by sales
   - Top 5 best-selling products
3. **Feature Engineering**:
   - Creating `TotalSales = Quantity × UnitPrice`
   - Extracting `Month` from `InvoiceDate`
4. **Customer Segmentation (RFM Analysis)**:
   - **Recency**: Days since last purchase
   - **Frequency**: Number of purchases
   - **Monetary**: Total spent by customer
5. **Customer Churn Analysis**:
   - Identifying customers who haven’t purchased in 90+ days
   - Visualizing churn distribution

## 🛠️ Installation & Setup
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/online-retail-analysis.git
   cd online-retail-analysis
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the script**:
   ```bash
   python retail_analysis.py
   ```

## 📈 Key Visualizations
- **Monthly Sales Trends** 📉
- **Top 5 Countries by Total Sales** 🌍
- **Top 5 Best-Selling Products** 🏆
- **Customer Churn Distribution** 📊

## 📌 Future Improvements
- Implementing **Machine Learning** for customer retention prediction
- Adding **Product Recommendation** based on past purchases


