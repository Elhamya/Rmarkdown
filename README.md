# 📊 Sales Analysis with R Markdown

A parameterised R Markdown project that performs **country-level sales analysis** using the [Online Retail dataset](https://archive.ics.uci.edu/ml/datasets/online+retail).  
This project demonstrates how to build **dynamic, reproducible reports** with R Markdown, enabling users to generate insights for different countries without changing the underlying code.

## 🚀 Features
- Parameterised reports (select country as a parameter).
- Automated data cleaning and preprocessing.
- Key sales KPIs:
  - Total revenue
  - Average order value (AOV)
  - Active customers
  - Repeat purchase rate
- Monthly sales trend visualisation.
- Top-selling and most-returned products.
- Easily extendable to multiple markets.

---
## 📂 Project Structure
```plaintext
.
├── data/
│   └── Online_Retail.csv       # Raw dataset
├── reports/
│   └── Sales_Report_UK.html    # Example output (UK)
│   └── Sales_Report_France.html # Example output (France)
├── scripts/
│   └── sales_analysis.Rmd      # Main R Markdown file
├── README.md    
