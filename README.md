**custodial-equipment-sales-analysis** 

<br>

**Portfolio project:** sales performance analysis by state, channel, and product subcategory (38k+ records).



**Goal:** Analyze US custodial equipment sales by state, channel, and product category. Compare actual revenue to targets, identify top/bottom performers, and highlight key trends for management decision-making.


<br>

📂 **Dataset**

Rows: ~38,880

Columns: 19

Coverage: All 50 US states + DC, multiple cities  

<br>

**Metrics:**

Sales: Units_Sold, Unit_Price, Revenue, Profit, Margin_Percent

Targets: Target_Units, Target_Revenue

Geography: 
State, City, Latitude, Longitude

Time: 
Date, Month

Channels: 
Sales_Channel (Direct, Distributor, Online)

Product taxonomy: 
Product_Category, Product_Subcategory

<br>

**Business Questions Answered**

Which states generated the most revenue, and how did they perform vs target?

How do sales channels compare in units sold, revenue, profit, and margin %?

Which product subcategories drive the most profit (and highest margins)?

What does the monthly revenue trend look like, and how is growth changing month-over-month?

Which cities are top and bottom performers by profit?

<br>

**🔑 Key Findings**

Geography: California and Texas lead in total revenue, but several Midwest states missed their revenue targets (<95% attainment).

Channels: Direct Sales delivers the most revenue, while Distributor margins are significantly lower — suggesting discounting.

Products: Walk-Behind Scrubbers dominate profit contribution, while smaller categories show higher % margins.

Trends: Revenue peaked in Q3 but slowed into Q4 — Q1 pipeline building will be critical.

Cities: Dallas and New York are strong profit centers, while smaller cities underperform consistently.

<br>

**📊 Visuals**


Top 10 States by Revenue
<img width="1600" height="1200" alt="top10_states_revenue" src="https://github.com/user-attachments/assets/74aa976c-6eeb-4a49-8765-7079a2ca98b5" />

Monthly Revenue Trend
<img width="2000" height="1000" alt="monthly_revenue_trend" src="https://github.com/user-attachments/assets/daa7795d-068e-4014-9834-c35cd964afe6" />


Month-over-Month % Growth
<img width="2000" height="800" alt="monthly_growth" src="https://github.com/user-attachments/assets/141a094f-963c-460f-a685-49c916bbf89d" />

<br>

**📁 Repo Contents**

Custodial_Sales_USA.ipynb
 → Jupyter notebook with full analysis & charts

<br>

 **→ Full dataset (simulated)**

 
[custodial_equipment_sales_USA_realistic.csv](https://github.com/user-attachments/files/22055301/custodial_equipment_sales_USA_realistic.csv)

<br>

outputs/ → exported CSVs & charts

[state_kpis.csv](https://github.com/user-attachments/files/22055027/state_kpis.csv)


[channel_performance.csv](https://github.com/user-attachments/files/22055024/channel_performance.csv)


[subcategory_profit.csv](https://github.com/user-attachments/files/22055030/subcategory_profit.csv)


[monthly_revenue.csv](https://github.com/user-attachments/files/22055032/monthly_revenue.csv)



[top10_cities_profit.csv](https://github.com/user-attachments/files/22055035/top10_cities_profit.csv)


[bottom10_cities_profit.csv](https://github.com/user-attachments/files/22055065/bottom10_cities_profit.csv)

<br>

**⚙️ Tools Used**

Python 3.11

pandas, numpy → data wrangling

matplotlib → data visualization

Jupyter Notebook → analysis environment

<br>

**🛠️ Skills Demonstrated**

Data Cleaning & Preparation – handled null values, stripped whitespace, standardized text columns

Datetime Handling – converted strings to datetime for monthly trend analysis

GroupBy & Aggregation – calculated KPIs by state, city, sales channel, and product subcategory

KPI Reporting – variance vs target, attainment %, margin %, and MoM growth metrics

Data Visualization – created stakeholder-ready bar and line charts with matplotlib

Export & Reuse – saved CSV summaries and PNG visuals for reporting and GitHub documentation

Portfolio Best Practices – structured project with clear README, outputs folder, and reproducible notebook
