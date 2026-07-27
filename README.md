------------------------------------------------------------
          AMAZON SALES ANALYSIS
     Python • Power BI • Machine Learning
------------------------------------------------------------
End-to-End Amazon Sales Analysis using Python, Power BI, EDA, Machine Learning, and Business Insights.
<h1 align="center">🛒 Amazon Sales Analysis using Python & Power BI</h1>

<p align="center">
  End-to-End Data Analytics Project involving Data Cleaning, Feature Engineering,
  Exploratory Data Analysis (EDA), Power BI Dashboarding, Machine Learning,
  and Business Recommendations.
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?style=for-the-badge&logo=numpy)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboarding-yellow?style=for-the-badge&logo=powerbi)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green?style=for-the-badge)
</p>

---

# 📌 Project Overview

Amazon hosts millions of products across multiple categories, making data-driven decision-making essential for improving customer satisfaction and business performance.

This project analyzes Amazon product data to uncover insights related to:

- Customer Ratings
- Product Pricing
- Discounts
- Product Popularity
- Savings Analysis
- Category Performance

The project follows a complete analytics lifecycle, beginning with raw data preprocessing and ending with business recommendations supported by Machine Learning.

---

# 🎯 Business Problem

Businesses need to understand:

✔ Which products perform best?

✔ How discounts impact customer ratings?

✔ Which categories attract more customer engagement?

✔ Which products should be promoted?

✔ How pricing strategies influence customer satisfaction?

This project answers these questions using analytical and visualization techniques.

---

# 🚀 Project Objectives

- Clean and preprocess raw Amazon product data.
- Perform comprehensive Exploratory Data Analysis (EDA).
- Create meaningful business metrics.
- Build an interactive Power BI Dashboard.
- Develop a Machine Learning model for rating prediction.
- Generate actionable business recommendations.

---

# 🏗️ Project Architecture

```text
Raw Amazon Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Power BI Dashboard
        │
        ▼
Machine Learning
        │
        ▼
Business Insights
        │
        ▼
Business Recommendations
```

---

# 📂 Dataset Information

The dataset contains information about Amazon products including:

| Feature | Description |
|----------|-------------|
| Product Name | Product Title |
| Category | Product Category |
| Actual Price | Original Product Price |
| Discounted Price | Selling Price |
| Discount Percentage | Discount Offered |
| Rating | Customer Rating |
| Rating Count | Number of Reviews |
| Review Content | Customer Reviews |

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

### Data Quality Checks

- Missing Value Analysis
- Duplicate Record Detection
- Null Value Treatment

### Data Transformation

- Currency Symbol Removal
- Numeric Conversion
- Data Type Standardization

### Data Validation

- Outlier Detection
- Consistency Checks
- Data Integrity Verification

---

# ⚙️ Feature Engineering

New business-oriented features were created:

| Feature | Purpose |
|----------|----------|
| Savings | Monetary Savings |
| Savings Percentage | Relative Savings |
| Price Category | Budget / Mid-Range / Premium |
| Rating Category | Low / Medium / High |
| Discount Category | Low / Medium / High |
| Popularity Category | Based on Review Volume |

These features enabled deeper analysis and improved machine learning performance.

---

# 📊 Exploratory Data Analysis (EDA)

More than 15 analytical visualizations were developed.

### Univariate Analysis

- Rating Distribution
- Price Distribution
- Discount Distribution
- Review Count Distribution

### Bivariate Analysis

- Rating vs Price
- Rating vs Discount
- Discount vs Savings
- Popularity vs Rating

### Multivariate Analysis

- Correlation Heatmap
- Category Performance Analysis
- Product Performance Comparison

### Advanced Insights

- Top Rated Products
- Most Reviewed Products
- Highest Savings Products
- Category Contribution Analysis

---

# 📈 Power BI Dashboard

An interactive 3-page Power BI Dashboard was developed.

## Executive Dashboard

### KPIs

- Total Products
- Average Rating
- Average Discount
- Total Savings

### Visualizations

- Category Analysis
- Rating Analysis
- Discount Analysis
- Product Performance

---

## Product Analysis Dashboard

### Visualizations

- Product Comparison
- Price Category Analysis
- Popularity Analysis
- Savings Analysis

---

## Advanced Insights Dashboard

### Visualizations

- Customer Behavior Analysis
- Discount Strategy Analysis
- Rating Performance Analysis
- Business Intelligence Insights

---

# 🤖 Machine Learning

## Model Used

### Linear Regression

The Linear Regression algorithm was used to predict customer ratings using:

- Actual Price
- Discounted Price
- Discount Percentage
- Rating Count
- Savings
- Savings Percentage

---

## Machine Learning Workflow

```text
Feature Selection
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Prediction
      │
      ▼
Evaluation
      │
      ▼
Business Recommendations
```

---

## Evaluation Metrics

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# 💡 Key Business Insights

### Insight 1

Most products maintain ratings above 4.0, indicating strong customer satisfaction.

### Insight 2

Higher discounts do not always result in better ratings.

### Insight 3

Products with higher review counts demonstrate greater customer trust.

### Insight 4

Premium products often generate larger savings values.

### Insight 5

Category performance varies significantly across pricing and ratings.

---

# 📌 Business Recommendations

### Recommendation 1

Promote highly rated products through featured listings.

### Recommendation 2

Improve product quality in lower-rated categories.

### Recommendation 3

Optimize discount strategies rather than relying solely on larger discounts.

### Recommendation 4

Increase visibility of highly rated products with fewer reviews.

---

# 📸 Dashboard Preview

## Executive Dashboard

---

## Product Analysis Dashboard

---

## Advanced Insights Dashboard

---
## Challenges Faced

- Cleaning inconsistent currency values
- Handling missing ratings
- Creating meaningful business features
- Designing interactive dashboards
- Building a machine learning model for prediction
  
# 🛠️ Technologies Used

| Category | Tools |
|-----------|--------|
| Programming | Python |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Dashboarding | Power BI |
| Machine Learning | Scikit-Learn |
| Environment | Jupyter Notebook |
| Data Source | Excel / CSV |

---

# 📁 Repository Structure

```text
Amazon-Sales-Analysis-Using-Python-and-PowerBI
│
├── Dataset
│   └── amazon.csv
│
├── Notebook
│   └── Amazon_Sales_Analysis.ipynb
│
├── PowerBI
│   └── Amazon_Dashboard.pbix
│
├── Report
│   └── Amazon_Project_Report.pdf
│
├── Presentation
│   └── Amazon_Project_Presentation.pptx
│
├── Dashboard Screenshots
│
├── EDA Visualizations
│
├── README.md
│
└── requirements.txt
```

---

# ▶️ Installation

Clone the repository

```bash
git clone https://github.com/your-narnesatwika/Amazon-Sales-Analysis-Using-Python-and-PowerBI.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 🔮 Future Scope

- Customer Segmentation
- Recommendation Systems
- Sales Forecasting
- Time Series Analysis
- NLP-based Review Analysis
- Advanced Machine Learning Models

---

# 👩‍💻 Author

## Narne Sathwika

### Aspiring Data Analyst | Business Analyst

**Skills**

- Python
- SQL
- Power BI
- Excel
- Pandas
- NumPy
- Machine Learning
- Data Visualization
- Business Analytics

---
## Contact

📧 Email:
narnesatwika1234@email.com

💼 LinkedIn:
https://www.linkedin.com/in/satwikanarne/

🐙 GitHub:
https://github.com/narnesatwika
<p align="center">
⭐ If you found this project useful, please consider giving it a star!
</p>
