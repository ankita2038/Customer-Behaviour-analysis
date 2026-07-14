# Customer Behavior Analysis using Python

## 📌 Project Overview

This project analyzes customer purchasing behavior using Python and Machine Learning techniques. The objective is to understand customer purchase patterns, segment customers based on their buying behavior, analyze churn, and provide business recommendations to improve customer retention and revenue.

This project was completed as part of the **Alfido Tech Data Analytics Internship**.

---

## 🎯 Objectives

- Perform Data Cleaning and Preprocessing
- Conduct Exploratory Data Analysis (EDA)
- Analyze Customer Purchase Patterns
- Perform Customer Segmentation using RFM Analysis
- Apply KMeans Clustering
- Analyze Customer Retention and Churn
- Generate Business Insights and Recommendations

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📂 Dataset Information

Dataset: **E-commerce Customer Behavior Dataset**

The dataset contains customer purchase records with the following attributes:

- Customer ID
- Purchase Date
- Product Category
- Product Price
- Quantity
- Total Purchase Amount
- Payment Method
- Customer Age
- Returns
- Customer Name
- Age
- Gender
- Churn

---

## 📊 Project Workflow

### 1. Data Collection

- Load CSV dataset
- Understand dataset structure

### 2. Data Cleaning

- Check missing values
- Remove duplicate records
- Convert date columns
- Verify data types

### 3. Exploratory Data Analysis (EDA)

- Gender Distribution
- Age Distribution
- Revenue by Category
- Revenue by Gender
- Payment Method Analysis
- Monthly Sales Trend
- Correlation Heatmap
- Returns Analysis

### 4. Feature Engineering

Created additional features such as:

- Purchase Month
- Purchase Year
- Total Spending

### 5. Customer Segmentation

Performed:

- RFM Analysis
- StandardScaler
- KMeans Clustering

Customers were grouped into four segments:

- High Value Customers
- Regular Customers
- Low Spending Customers
- Potential Churn Customers

### 6. Purchase Pattern Analysis

Analyzed:

- Product Categories
- Customer Spending
- Payment Methods
- Monthly Sales
- Top Customers

### 7. Churn Analysis

Analyzed customer churn using:

- Churn Distribution
- Gender vs Churn
- Product Category vs Churn
- Payment Method vs Churn

---

## 📈 Key Insights

- Books and Clothing generated the highest revenue.
- Customers aged 30–50 contributed the highest sales.
- Digital payment methods were the most commonly used.
- Approximately 20% of customers had churned.
- High-value customers generated a significant share of total revenue.

---

## 💡 Business Recommendations

1. Launch loyalty programs for high-value customers.
2. Offer personalized discounts to churn-risk customers.
3. Increase promotions for Books and Clothing categories.
4. Encourage digital payment methods using cashback offers.
5. Use customer segmentation for targeted marketing campaigns.

---

## 📁 Project Structure

```
Customer_Behavior_Project/
│
├── Customer_Behavior_Analysis.ipynb
├── Customer_Behavior_Report.pdf
├── ecommerce_customer_data_custom_ratios.csv
├── README.md
└── requirements.txt
```

---

## ▶️ How to Run the Project

1. Clone or download the project.
2. Install the required libraries.

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.

```bash
jupyter notebook
```

4. Run all cells sequentially.

---

## 📌 Results

The project successfully:

- Cleaned and prepared the dataset
- Performed Exploratory Data Analysis
- Segmented customers using RFM and KMeans
- Identified customer purchase patterns
- Analyzed customer churn
- Generated actionable business recommendations

---

## 👨‍💻 Author

**Shubham Yadav**

Data Analytics Intern

---

## 📄 License

This project is developed for educational and internship purposes.
