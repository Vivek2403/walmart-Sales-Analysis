# walmart-Sales-Analysis

Walmart Sales Data Analysis

Introduction:-

This project dives into Walmart's sales data to identify top-performing branches and products, uncover sales trends, and understand customer behavior. By leveraging these insights, we aim to optimize sales strategies by allocating resources effectively, predicting demand for better inventory management, and personalizing the customer experience through targeted promotions and recommendations, ultimately leading to increased sales, happier customers, and data-driven decision-making.


Dataset Description:-

This dataset contains sales transactions from a three different branches of Walmart, respectively located in Mandalay, Yangon and Naypyitaw. The data contains 17 columns and 1000 rows.This dataset was taken from Kaggle and the link for data set is https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting




Customer-Centric Analysis:

->Product Analysis: Identify top-performing product lines, explore underperforming categories, and understand customer preferences across different product segments.

->Sales Analysis: Analyze sales trends to assess the effectiveness of past sales strategies, uncover seasonal patterns, and predict future demand for optimized inventory management.

->Customer Segmentation: Discover distinct customer segments based on demographics and purchasing behavior. Analyze the profitability of each segment to tailor marketing strategies and enhance customer experience.


This revised list reframes the analyses with a customer-centric approach. It highlights understanding customer preferences and behavior as a key driver for optimizing product lines, sales strategies, and ultimately, customer satisfaction and profitability.

Approaches used:-

Data Preparation:

->Data Inspection: We meticulously examined the data to identify and address any missing values. Depending on the data and analysis goals, we might choose to impute missing values, exclude rows with missing data, or flag them for further investigation.

->Database Creation (Optional): If necessary, a database will be established to efficiently store and manage the Walmart sales data. Tables will be designed with appropriate data types and constraints, potentially including NOT NULL constraints to minimize missing values.

-->Feature Engineering:

To enrich the data and uncover deeper insights, we will create new features based on existing ones:

Time-based Features:

time_of_day: Categorize transactions into morning, afternoon, and evening to analyze sales patterns throughout the day.
day_name: Extract the day of the week (Monday, Tuesday, etc.) to identify peak business days for each branch.
month_name: Extract the month (January, February, etc.) to determine seasonal sales trends.


->Exploratory Data Analysis (EDA):

This phase will leverage various visualization and analysis techniques to answer the project's questions and objectives. These might include:

Identifying top-performing products and categories.
Analyzing sales trends across time periods.
Segmenting customers based on purchase behavior and profitability.
Uncovering correlations between variables like time of day, day of the week, and sales volume.
The outcome of the EDA will provide a comprehensive understanding of the Walmart sales data, laying the foundation for further analysis and actionable insights.

This revised text clarifies the purpose of data inspection, acknowledges potential options for handling missing values, and highlights the specific features created through engineering. It emphasizes the role of EDA in uncovering valuable insights for the project.



Business Questions To Answer

Generic Question

1)How many unique cities does the data have?
2)In which city is each branch?

Product Related Questions:-

1)How many unique product lines does the data have?
2)What is the most common payment method?
3)What is the most selling product line?
4)What is the total revenue by month?
5)What month had the largest COGS?
6)What product line had the largest revenue?
7)What is the city with the largest revenue?
8)What product line had the largest VAT?
9)Fetch each product line and add a column to those product line showing "Good", "Bad". Good if its greater than average sales
10)Which branch sold more products than average product sold?
11)What is the most common product line by gender?
12)What is the average rating of each product line?

Sales Related Questions:-

1)Number of sales made in each time of the day per weekday
2)Which of the customer types brings the most revenue?
3)Which city has the largest tax percent/ VAT (Value Added Tax)?
4)Which customer type pays the most in VAT?

Customer Related Questions:-

1)How many unique customer types does the data have?
2)How many unique payment methods does the data have?
3)What is the most common customer type?
4)Which customer type buys the most?
5)What is the gender of most of the customers?
6)What is the gender distribution per branch?
7)Which time of the day do customers give most ratings?
8)Which time of the day do customers give most ratings per branch?
9)Which day fo the week has the best avg ratings?
10)Which day of the week has the best average ratings per branch?

