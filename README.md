# Funnel-Analysis
Customer Funnel Analysis using Python | An end-to-end data analytics project focused on understanding customer behaviour, tracking conversion rates across different funnel stages, analysing customer transition time, and identifying city-wise conversion patterns using Python, Pandas, NumPy, Matplotlib, Seaborn and Plotly .

## 📌 Project Overview

Customer Funnel Analysis is a Python-based data analytics project that focuses on understanding customer behaviour throughout the e-commerce purchasing journey.

The project analyses customer activities across different funnel stages, from browsing a product to completing a checkout and providing a review or requesting a return/refund.

The main objective is to understand customer conversion patterns, measure the time taken to move between different stages, and analyse funnel performance across different cities.

By transforming raw customer data into meaningful visualisations, this project demonstrates how data analytics can help businesses understand customer behaviour and identify opportunities to improve conversions.

## 🎯 Project Objectives

- Perform data cleaning and preprocessing.
- Analyse customer distribution across different cities.
- Understand age-wise customer distribution.
- Analyse customer activities and purchasing patterns.
- Calculate monthly order amounts and subscription revenue.
- Analyse payment methods and city-wise revenue.
- Build an end-to-end customer conversion funnel.
- Calculate stage-wise customer conversion percentages.
- Measure customer transition time between funnel stages.
- Perform city-wise customer funnel analysis.

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data analysis and programming |
| Pandas | Data cleaning, manipulation and analysis |
| NumPy | Numerical calculations |
| Matplotlib | Data visualisation |
| Seaborn | Statistical visualisation |
| Plotly | Interactive charts and funnel visualisations |
| Jupyter Notebook | Development and analysis environment |

## 📂 Dataset Description

The project uses five CSV datasets:

| Dataset | Description |
|---|---|
| `cust_activity.csv` | Customer activities and activity dates |
| `cust_bio.csv` | Customer demographic information |
| `cust_sub.csv` | Customer subscription information |
| `sp.csv` | Subscription plan details |
| `orders (2).csv` | Customer order and payment information |

These datasets are combined using customer IDs and subscription plan IDs to perform different analytical operations.

## 🔍 Project Workflow

### 1. Data Loading & Exploration

- Imported datasets using Pandas.
- Examined dataset dimensions and column names.
- Checked data types.
- Identified missing values.
- Checked duplicate records.

### 2. Exploratory Data Analysis (EDA)

Performed the following analyses:

| Analysis | Visualisation |
|---|---|
| City-wise customer count | Bar Chart |
| Age-range customer distribution | Pie Chart |
| Customer activity count | Bar Chart |
| Month-wise total order amount | Line Chart |
| Subscription plan-wise revenue | Bar Chart |
| City-wise total revenue | Bar Chart |
| Payment mode distribution | Donut Chart |
| Payment mode-wise amount | Strip Plot |

### 3. Customer Funnel Analysis

Created a customer funnel to understand how customers progress through different stages of the purchasing journey.

**Funnel stages:**

1. Browse
2. Sign Up
3. Add to Cart
4. Checkout
5. Review
6. Return/Refund

The funnel analysis focuses on:

- Number of unique customers at each activity stage.
- Stage-wise conversion percentages.
- Customer drop-off patterns.
- Visual representation of the complete funnel.

### 4. Customer Transition Time Analysis

Analysed the time taken by individual customers to move between different funnel activities.

Calculated the date differences between:

- Browse → Sign Up
- Sign Up → Add to Cart
- Add to Cart → Checkout
- Checkout → Review
- Checkout → Return/Refund

Also calculated the average transition days for each activity transition.

### 5. City-wise Funnel Analysis

Developed a reusable Python function to analyse customer funnel performance for a selected city.

This analysis helps compare customer activity patterns and conversion percentages across geographical locations.

## 📊 Key Analytical Areas

| Business Area | Analytical Purpose |
|---|---|
| Customer Behaviour | Understand customer activities |
| Customer Segmentation | Analyse age and city distribution |
| Revenue Analysis | Evaluate monthly and city-wise revenue |
| Subscription Analysis | Understand subscription plan revenue |
| Payment Analysis | Examine payment method preferences |
| Conversion Analysis | Track customer funnel performance |
| Transition Analysis | Measure time between funnel stages |
| Geographical Analysis | Evaluate city-wise funnel performance |

## 💡 Business Value

This project demonstrates how businesses can use customer activity data to:

- Understand customer purchasing behaviour.
- Monitor conversion performance at different stages.
- Identify potential customer drop-off points.
- Evaluate the time customers take to complete purchases.
- Compare funnel performance across cities.
- Understand payment preferences and revenue patterns.
- Identify areas where improvements in the customer journey may be needed.

## ⚙️ How to Run This Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/your-username/customer-funnel-analysis.git
```

**Step 2: Navigate to the project folder**

```bash
cd customer-funnel-analysis
```

**Step 3: Install required libraries**

```bash
pip install pandas numpy matplotlib seaborn plotly jupyter
```

**Step 4: Add the CSV datasets**

Place all five required CSV files in the project directory.

**Step 5: Launch Jupyter Notebook**

```bash
jupyter notebook
```

**Step 6: Open the notebook**

Open `Funnel_Analysis_project.ipynb` and execute the cells to reproduce the analysis.

## 📁 Project Structure

```text
customer-funnel-analysis/
│
├── Funnel_Analysis_project.ipynb
│
├── cust_activity.csv
├── cust_bio.csv
├── cust_sub.csv
├── sp.csv
├── orders (2).csv
│
└── README.md
```

## 🚀 Future Improvements

- Build an interactive dashboard using Power BI or Tableau.
- Add automated funnel conversion reporting.
- Perform deeper customer segmentation.
- Identify factors associated with customer drop-offs.
- Develop predictive models for customer conversion.

## 👨‍💻 Author

**Anurag Singh**

Aspiring Data Analyst | Python | SQL | Excel | Data Visualisation

Interested in transforming raw data into meaningful insights and solving real-world business problems through data analytics.

---

<p align="center">
  ⭐ If you find this project useful, consider giving this repository a star!
</p>
