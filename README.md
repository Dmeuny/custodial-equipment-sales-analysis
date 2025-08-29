# custodial-equipment-sales-analysis
Portfolio project: sales performance analysis by state, channel, and product subcategory (38k+ records).



Goal: Analyze US custodial equipment sales by state, channel, and product category. Compare actual revenue to targets, identify top/bottom performers, and highlight key trends for management decision-making.




📂 Dataset

Rows: ~38,880

Columns: 19

Coverage: All 50 US states + DC, multiple cities

Metrics:

Sales: Units_Sold, Unit_Price, Revenue, Profit, Margin_Percent

Targets: Target_Units, Target_Revenue

Geography: State, City, Latitude, Longitude

Time: Date, Month

Channels: Sales_Channel (Direct, Distributor, Online)

Product taxonomy: Product_Category, Product_Subcategory



❓ Business Questions Answered

Which states generated the most revenue, and how did they perform vs target?

How do sales channels compare in units sold, revenue, profit, and margin %?

Which product subcategories drive the most profit (and highest margins)?

What does the monthly revenue trend look like, and how is growth changing month-over-month?

Which cities are top and bottom performers by profit?



🔑 Key Findings

Geography: California and Texas lead in total revenue, but several Midwest states missed their revenue targets (<95% attainment).

Channels: Direct Sales delivers the most revenue, while Distributor margins are significantly lower — suggesting discounting.

Products: Walk-Behind Scrubbers dominate profit contribution, while smaller categories show higher % margins.

Trends: Revenue peaked in Q3 but slowed into Q4 — Q1 pipeline building will be critical.

Cities: Dallas and New York are strong profit centers, while smaller cities underperform consistently.



📊 Visuals
Top 10 States by Revenue

Monthly Revenue Trend

Month-over-Month % Growth



📁 Repo Contents

Custodial_Sales_USA.ipynb
 → Jupyter notebook with full analysis & charts

custodial_equipment_sales_USA_realistic.csv
 → dataset (simulated)

outputs/ → exported CSVs & charts

state_kpis.csv

channel_performance.csv

subcategory_profit.csv

monthly_revenue.csv

top10_cities_profit.csv

bottom10_cities_profit.csv

top10_states_revenue.png

monthly_revenue_trend.png

monthly_growth.png



⚙️ Tools Used

Python 3.11

pandas, numpy → data wrangling

matplotlib → data visualization

Jupyter Notebook → analysis environment



🛠️ Skills Demonstrated

Data Cleaning & Preparation – handled null values, stripped whitespace, standardized text columns

Datetime Handling – converted strings to datetime for monthly trend analysis

GroupBy & Aggregation – calculated KPIs by state, city, sales channel, and product subcategory

KPI Reporting – variance vs target, attainment %, margin %, and MoM growth metrics

Data Visualization – created stakeholder-ready bar and line charts with matplotlib

Export & Reuse – saved CSV summaries and PNG visuals for reporting and GitHub documentation

Portfolio Best Practices – structured project with clear README, outputs folder, and reproducible notebook
