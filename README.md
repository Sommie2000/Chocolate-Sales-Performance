## CHOCOLATE-SALES-ANALYSIS | Revenue, Trends and Insights
Excel | Chocolate Sale Data| From Raw Data to Business Insights

### TABLE OF CONTENT
* [Project Overview](#project-overview)
* [Dataset Overview](#dataset-overview)
* [Data Cleaning](#data-cleaning)
* [Excel Dashboard](#excel-dashboard)
* [Dashboard](#dashboard)
* [Key Insights](#key-insights)
* [Interactive Analysis](#interactive-analysis)
* [Recommendation](#recommendation)
* [Data Source](#data-source)


### PROJECT OVERVIEW
This Project analyzes chocolate sales data to uncover trends in revenue, product performance and dominance, market strength, seasonal trend, regional sales and top salesperson performance. I used power query editor for data cleaning and excel for data transformation and visualization, the project turns raw transaction records into strategic business insights and decision making.


### DATASET OVERVIEW
Columns:
- Sales Person	
- Country	
- Product	
- Date	
- Month	
- Year	
- Corrected Date	
- Amount	
- Boxes Shipped

Dataset Sample Preview
|Sales Person|	Country|	Product	Date|	Month|	Year|	Corrected Date|	Amount|	Boxes Shipped|
|------------|---------|--------------|------|------|---------------|-------|--------------|
|Jehu Rudeforth|	UK|	Mint Chip Choco|	4/1/2022|	Jan|	2022|	4-Jan-22|	$5.3K|	180|
|Van Tuxwell|	India|	85% Dark Bars|	1/8/2022|	Jan|	2022|	5-Jan-22|	$7.9K|	94|
|Gigi Bohling|	India|	Peanut Butter Cubes|	7/7/2022|	Jan|	2022|	6-Jan-22|	$4.5K|	91|
|Jan Morforth|	Australia|	Peanut Butter Cubes|	27/04/2022|	Jan|	2022|	7-Jan-22|	$12.7K|	342|
|Jehu Rudeforth|	UK|	Peanut Butter Cubes|	24/02/2022|	Jan|	2022|	8-Jan-22|	$13.7K|	184|


[Dataset file showing the pivot tables][Chocolate Sales 3.xlsx](https://github.com/user-attachments/files/26504748/Chocolate.Sales.3.xlsx)

### DATA CLEANING
- Changed date and amount datatype to date and currency format
- Removed, duplicate, missing or invalid values
- Created new columns for corrected date and year


### EXCEL DASHBOARD 
KPI Cards
* 💹 Total Revenue: $19792M
* 🍫 Total Boxes Shipped: $540K
* 📈 Average Revenue per Sale: $6K
* 🍫 Average Boxes Shipped: 165

The Excel dashboard includes the following charts:
- 💹 Sales performance in each country (sales by country)
- 📈 Monthly sales trend
- 🍫 Product sales performance (sales by products)
- 🧑‍🤝‍🧑 Top 10 sales Person
- 📊 Sales by total boxes
- 🗺️ Regional sales performance for top 5 products


### DASHBOARD

(![Chocolate Sales Dashboard 2](https://github.com/user-attachments/assets/cdbb1034-a3bc-4fee-bc9f-b67590330ff2)


### KEY INSIGHTS 
1. Australia emerged as the highest revenue generating country with 18%, indicating strong market demand and effective regional sales performance while New Zealand generated the lowest revenuewith 15%
2. Revenue peaked in June and July, revealing a possible seasonal buying pattern, this insight could be;
   > Seasonal inventoy planning, Targeted marketing campaigns and Promotional timing strategies
3. Smooth silky salty chocolate product contributed the highest revenue, suggesting strong product-market fit, customer preference and demand while the product with the lowest revenue is the 70% dark bites
4. The top sales person is Ches Bonnell, Ches Bonnell generated the highest sales revenue, demostrating strong sales effectiveness
5. The top selling product with the highest boxes shipped is the 50% dark bites chocolate even if it didnt drive the highest sales revenue

### INTERACTIVE ANALYSIS 
To enhance usability, I integrated a Year Slicer, allowing dynamic filtering of the performance metrics across different years. 
This helps uncover;
- Year-over-year performance change
- Shifts in product demand
- Trend Analysis
- Performance tracking by period
- Market growth patterns

### RECOMMENDATION   
* Expand distribution of smooth silky salty chocolate and review pricing strategies for low margin products such as 70% dark bites and caramel stuffed bars chocolates
* Analyze underperforming products and months for improvement opportunities
* Stregthening top markets in Australia and also support underperforming countries
* The company can optimize revenue growth and sales strategy
* Leverage peak months (june and july) with promotions

### DATA SOURCE
This data was gotten from Kaggle
[Download here](https://www.kaggle.com/datasets?search=chocolate+sales)

