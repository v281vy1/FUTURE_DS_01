# FUTURE_DS_01 – Business Sales Dashboard (E-commerce)
“Task 1 – Business Sales Dashboard (E-commerce) | Future Interns Data Science &amp; Analytics Program”

##  Project Overview
This repository contains **Task 1** of the Future Interns Data Science & Analytics Program.  
The goal is to analyze an e-commerce dataset, derive insights, and build an **interactive business sales dashboard**.

##  Repository Structure
- `data/` – raw and cleaned dataset (CSV)
- `notebooks/` – Colab notebook with data cleaning & analysis
- `images/` – screenshots of the dashboard
- `README.md` – project documentation
  

##  Dataset Information
This project uses the **UK Online Retail Dataset** (available on [Kaggle](https://www.kaggle.com/carrie1/ecommerce-data)).

- Transactions from Dec 2010 to Dec 2011
- Columns include `InvoiceNo`, `StockCode`, `Description`, `Quantity`, `InvoiceDate`, `UnitPrice`, `CustomerID`, `Country`

### 🔹 Note on Data Files
- The **raw dataset** is too large (>25 MB) to be uploaded directly to GitHub.
- Instead:
  - A **cleaned dataset (`cleaned_ecommerce.csv`)** is provided in this repo.
  - The full raw dataset can be downloaded from Kaggle: [UK Online Retail Dataset](https://www.kaggle.com/carrie1/ecommerce-data).
- If you want to try the cleaning process yourself, run `data_cleaning.ipynb` on the raw dataset.

##  Key KPIs
- Total Sales
- Total Orders
- Average Order Value (AOV)
- Best-Selling Products
- High-Revenue Categories
- Sales Trend over Time

##  Dashboard Highlights
- Sales overview with KPIs
- Category & Product performance
- Interactive filters (date, category, product)
- Sales trends visualization

![Dashboard Overview](images/overview.png)

## Insights (Summary)
- **Data coverage:** Dec 2010 → Mar 2011 (4 months, ~83k transactions).
- **Monthly trend:** Peak sales in Dec 2010, with a post-holiday dip in Jan and partial recovery in Feb–Mar.
- **Best-selling products:** <fill from top_products chart>.
- **Top countries:** <fill from top_countries chart>.
- **KPIs:** 
  - Total Revenue = £<TOTAL_REVENUE>
  - Total Orders = <TOTAL_ORDERS>
  - Average Order Value (AOV) = £<AOV>
  - Customers = <CUSTOMERS>
- **Business takeaway:** Seasonal spikes (holidays), strong product concentration, and UK dominance in revenue.


##  Tech Stack
- **Python (Pandas, Seaborn, Matplotlib, Plotly)** for cleaning & analysis
- **Power BI** for interactive dashboard
- **GitHub** for version control

##  How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/v281vy1/FUTURE_DS_01.git
