# 📊 Sales Transaction Automation using Python & Power BI

## Overview

This project automates the process of cleaning, analyzing, and visualizing sales transaction data using **Python** and **Power BI**. It reads raw sales data from a CSV file, performs data cleaning and preprocessing, generates summary reports and charts, and prepares the data for an interactive Power BI dashboard.

The automation workflow reduces manual effort and ensures that reports and dashboards can be updated quickly whenever new sales data becomes available.

---

## Features

* Read sales transaction data from a CSV file
* Remove duplicate and empty records
* Handle missing values automatically
* Standardize text formatting for consistency
* Convert columns to appropriate data types
* Calculate total sales for each transaction
* Generate a cleaned dataset
* Create an Excel summary report
* Automatically generate charts
* Integrate with Power BI for dashboard visualization

---

## Technologies Used

* Python
* Pandas
* Matplotlib
* OpenPyXL
* Power BI
* Microsoft Excel

---

## Dataset

The dataset contains sales transaction records with the following fields:

| Column         | Description             |
| -------------- | ----------------------- |
| Order_ID       | Unique order identifier |
| Date           | Transaction date        |
| Customer_Name  | Customer name           |
| Region         | Sales region            |
| Product        | Product purchased       |
| Quantity       | Quantity sold           |
| Price          | Price per unit          |
| Salesperson    | Sales representative    |
| Payment_Status | Payment status          |

---

## Project Structure

```text
Sales-Transaction-Automation/
│
├── automation.py
├── raw_data.csv
├── cleaned_data.csv
├── summary_report.xlsx
├── region_chart.png
├── product_chart.png
├── payment_chart.png
├── salesperson_chart.png
├── dashboard.pbix
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/<your-username>/sales-transaction-automation.git
```

Move into the project folder:

```bash
cd sales-transaction-automation
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Place the latest sales dataset in the project folder.
2. Rename it to **raw_data.csv** (if needed).
3. Run the automation script:

```bash
python automation.py
```

The script will automatically:

* Read the raw dataset
* Remove duplicate records
* Remove blank rows
* Handle missing values
* Standardize text formatting
* Convert data types
* Calculate total sales
* Save the cleaned dataset
* Generate a summary report
* Create chart images

---

## Output Files

After execution, the following files are generated:

* **cleaned_data.csv** – Cleaned sales dataset
* **summary_report.xlsx** – Statistical summary
* **region_chart.png** – Orders by region
* **product_chart.png** – Product distribution
* **payment_chart.png** – Payment status distribution
* **salesperson_chart.png** – Sales by salesperson

---

## Power BI Dashboard

Import **cleaned_data.csv** into Power BI to build interactive reports.

Suggested dashboard components:

* KPI Cards

  * Total Sales
  * Total Orders
  * Total Customers
  * Average Sales
  * Pending Payments

* Visualizations

  * Sales by Region
  * Sales by Product
  * Sales by Salesperson
  * Payment Status
  * Monthly Sales Trend

* Slicers

  * Date
  * Region
  * Product
  * Salesperson
  * Payment Status

Whenever a new dataset is available:

1. Replace **raw_data.csv** with the latest file.
2. Run **automation.py**.
3. Open **dashboard.pbix**.
4. Click **Home → Refresh** to update all dashboard visuals.

---

## Learning Outcomes

This project demonstrates:

* Data cleaning with Pandas
* Data preprocessing and transformation
* Automation using Python
* Report generation in Excel
* Data visualization with Matplotlib
* Power BI dashboard integration
* End-to-end data analytics workflow

## Future Enhancements

* Interactive visualizations using Plotly
* Automated email reports
* Scheduled execution using Task Scheduler or Cron
* Database integration (MySQL or PostgreSQL)
* Cloud deployment
* Real-time dashboard updates

## Author

**Samraddhi**

If you found this project useful, consider giving the repository a ⭐ on GitHub.

