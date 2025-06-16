# E-commerce Behavioral & Shipping Metrics Analysis – UK Company

## 📌 Overview
Analyzed a UK-based e-commerce dataset to extract behavioral insights using **RFM segmentation**, **basket analysis**, and **shipping performance**. Developed a business-ready dashboard in **Power BI**.

## 🧰 Tools & Tech Stack
- **Languages & Libraries**: Python (Pandas, NumPy, Seaborn, Matplotlib), SQL (via pandasql)  
- **Dashboarding**: Power BI (`.pbix` included)  
- **Analysis Types**: RFM scoring, basket/co-purchase analysis, shipping delay metrics

## 🔍 Key Analyses
### 🧠 RFM Segmentation
- **Recency**: Days since last purchase  
- **Frequency**: Number of purchases  
- **Monetary**: Total purchase value  
- Customers were grouped into behavior-based segments (Champions, At Risk, Hibernating, etc.)

### 🛍 Basket Analysis
- Identified frequently co-purchased item pairs using basic association rules.  
- Revealed item clusters used to recommend bundle offers.

### 🚚 Shipping Metrics
- Evaluated delivery times, order status, and cost-based delays.  
- Flagged orders with late shipments and high delivery charges for optimization.

## 📊 Power BI Dashboard
Key features:
- Interactive **customer segment breakdown** via RFM clusters  
- **Shipping KPI visuals**: late vs. on-time delivery, avg shipping cost by region  
- Time-series trends on sales, revenue, and regional order volumes

## 💼 Business Value
- Enabled **targeted retention strategies** using RFM segmentation.  
- Informed **operational improvements** by highlighting shipping inefficiencies.  
- Delivered an executive-ready dashboard for actionable decision-making.

## ▶️ How to Run
```bash
git clone <this-repo>
cd Ecommerce-UK-RFM-Shipping-Analysis
# Launch Jupyter Notebook
jupyter notebook "Ecommerce Analysis UK based Company.ipynb"
