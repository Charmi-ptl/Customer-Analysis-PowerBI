# Customer Analysis: Google Colab & Power BI  

This project provides an end-to-end customer data analysis, starting with data preprocessing and exploratory data analysis (EDA) in Google Colab, followed by interactive visualizations in Power BI.  

#  Project Overview  
The dataset contains customer information, including:  
Demographics (Age, Gender)  
Purchase Behavior (Basket Count, Tenure)  
Shopping Patterns (Products Bought Per Basket)  

# Project Structure  

Customer-Analysis/ │── data/ # Raw datasets │ ├── customers.csv # Customer details │ ├── basket.csv # Shopping basket data │ │── analysis/ # Google Colab notebook │ ├── customer_analysis.ipynb # Data analysis & EDA │ │── visualization/ # Power BI dashboard │ ├── Customer_Analysis.pbix # Final interactive report │ │── README.md # Project documentation

yaml

# 1️ Data Analysis in Google Colab
Steps Performed: 
Loaded Datasets (Customers & Basket Transactions)  
Checked for Missing Values & Data Types  
Merged Data Using `customer_id`  
Handled Data Issues (e.g., incorrect customer ages)  
Generated Summary Statistics 

* File Used: `analysis/customer_analysis.ipynb`  

---

# 2️ Power BI Interactive Dashboard  
Visualizations Created:  
Customer Age Distribution → Histogram to analyze age trends  
Gender Breakdown → Pie Chart to compare male vs. female customers  
Basket Count Analysis → Bar Chart to show items per transaction  
Customer Tenure Trends → Line Chart to see long-term customers  

* File Used: `visualization/Customer_Analysis.pbix`  

# How to Use This Project  

Step 1️⃣: Clone the Repository  
```bash
git clone https://github.com/yourusername/Customer-Analysis.git

Step 2️⃣: Run the Google Colab Notebook
Open customer_analysis.ipynb in Google Colab

Run all cells to analyze the data

Step 3️⃣: Explore the Power BI Dashboard
Open Customer_Analysis.pbix in Power BI Desktop

Use filters to interact with the data

# Key Insights from the Analysis
 Age Issues Detected → Some customers had unrealistic ages (e.g., 2022 years old), which were corrected.
 Most Customers Buy Exactly 2 Items per Basket → 75% of transactions have only 2 products.
 Male Customers Dominate (~80%) → The majority of customers in the dataset are male.
 Tenure Shows Long-Term Customers → The median tenure is ~45 months, indicating long-time buyers.

# Tools & Technologies Used
Python (Google Colab) → Data cleaning, merging, and EDA
Pandas, Matplotlib, Seaborn → Data processing & visualization
Power BI → Interactive dashboard creation

