# Retail Sales Analysis
## Brief Project Description
This project analyzes retail sales data from 2012 to 2015 to evaluate business performance and identify the leading products and strongest regions by revenue. By examining these multi-year transaction records, the analysis aims to achieve four critical objectives: determining which product categories generate the highest sales, uncovering sales trends over time, mapping sales and profit distribution across global regions, finding the relationship between sales and profit, evaluating how discounts affect profits.
Ultimately, the project aims to reveal trends and proffer actionable recommendations to influence management decisions to improve sales for low performing products, further explore the high-performing regions and consider reviewing discount strategies, all aimed at boosting performance and increasing profits for the business.
### Dataset Used
The dataset used in this project is the **Retail Sales Analysis Data.csv** dataset
### Project Research Questions
- What product categories are the most profitable?
- How do sales and profits vary by region?
- Are there any noticeable trends in sales over time?
- How are sales and profits related?
- Is there a correlation between discount and profit?
### Dataset Details
- **Name:** Retail Sales Analysis Data.csv
- **Size:** 1,000 rows and 24 columns
- **Key fields/columns used:** Sales, Profit, Region, Discount, Date
- **Pre-processing/Cleaning Steps:**
  - Removed column with null values
  - Converted the date field data to Date/Time data type
### Technologies Used
- **Languages and Libraries:** Python - Pandas, NumPy, SQL, Matplotlib, Seaborn
- **Tools:** Google Colab, Github
- **Data Visualization:** Python Matplotlib and Seaborn Libraries
### Analysis and Visualizations
Top Product Categories

<img src="Assets/Top%2010%20Products.png" width="400" alt="Top Products">
<img src="Assets/Sales%20by%20Product%20Category.png" width="400" alt="Total Sales by Product Category">


Top Regions by Sales

<img src="Assets/Top%2010%20Regions.png" width="400" alt="Top 10 Regions">


Sales vs Profit

<img src="Assets/Sales%20vs%20Profit.png" width="400" alt="Sales vs Profit">


Monthly Sales Over Time

<img src="Assets/Monthly%20Sales%20Over%20Time.png" width="400" alt="Monthly Sales Over Time">


Heatmap of Sales by Region and Category

<img src="Assets/Heatmap%20of%20Sales%20by%20Region%20and%20Category.png" width="400" alt="Heatmap of Sales by Region and Category">

## Conclusion
The analysis has revealed a strong business generating 1,710,971.47 in total sales and 288,920.44 in profit, anchored by Technology (756,983.02 sales; 145,068.68 profit). In terms of regional sales performance, Western Europe (259,576.28) and Oceania (220,809.08) lead in total sales revenue, and Western Europe (48,124.20) and Central Europe (35,160.85) generate the highest overall profit figures. 
While monthly sales trend upward over time with seasonal surges and correlate positively with profit (with r being approximately 0.53), our discount vs profit analysis proves a clear negative correlation (r = -0.51), which clearly shows that aggressive discounts reduce profits, which is quite logical.
To optimize business performance, management must dial down discounts, re-evaluate sales strategies on low-selling products like office supplies, and leverage the already strong market performance in the more profitable regions like Western Europe and Oceania. Next, we should look closely at customer segments to spot and fix unprofitable orders.


