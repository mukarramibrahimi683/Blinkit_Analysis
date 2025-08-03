Blinkit Sales Data Analysis
This project performs an in-depth analysis of the Blinkit sales dataset. The primary goal is to clean the data, calculate key performance indicators (KPIs), and create visualizations to uncover insights into sales performance.

📂 Dataset
The analysis is based on the blinkit_data.csv file, which contains 8,523 rows and 12 columns.

Data Columns:
Item Fat Content: The fat content of the product (e.g., Low Fat, Regular).

Item Identifier: A unique ID for each product.

Item Type: The category to which the product belongs.

Outlet Establishment Year: The year the outlet was established.

Outlet Identifier: A unique ID for each outlet.

Outlet Location Type: The type of location where the outlet is (e.g., Tier 1, Tier 2).

Outlet Size: The size of the outlet (e.g., Small, Medium, Large).

Outlet Type: The type of outlet (e.g., Supermarket Type1).

Item Visibility: The percentage of the total display area in the store for a specific product.

Item Weight: The weight of the product.

Sales: The total sales of the product in a particular outlet.

Rating: The customer rating of the product.

🧹 Data Cleaning and Preparation
Before analysis, the dataset was cleaned and prepared through the following steps:

Handling Missing Values: The Item Weight column contained 1,463 null values, which were filled using the mean of the existing values.

Standardizing Categorical Data:

In Item Fat Content, inconsistent values like 'LF', 'low fat', and 'reg' were standardized to 'Low Fat' and 'Regular'.

In Outlet Size, 'High' was replaced with 'Large' for better clarity.

Duplicate Check: The dataset was checked for duplicate rows, and none were found.

📊 Key Performance Indicators (KPIs)
Several key metrics were calculated to measure business performance:

Total Sales: $1,201,681

Average Revenue Per Sale: $141.0

Average Product Rating: 4.0

📈 Visualizations
Data visualizations were created to explore sales trends across different categories:

1. Total Sales by Item Fat Content
A pie chart was used to show the distribution of sales based on item fat content.

2. Total Sales by Item Type
A bar chart illustrates the total sales for each item type, with "Fruits and Vegetables" and "Snack Foods" being the highest-grossing categories.

3. Total Sales by Outlet Location and Fat Content
A grouped bar chart compares the sales of 'Low Fat' and 'Regular' items across different outlet location tiers.

4. Total Sales by Outlet Establishment Year
A line chart shows the trend of total sales based on the year the outlets were established.

5. Total Sales by Outlet Size
A pie chart breaks down the total sales by the size of the outlet, highlighting the contribution of each size category.

🛠 Libraries Used
The analysis was performed using the following Python libraries:

pandas: For data manipulation and analysis.

numpy: For numerical operations.

matplotlib: For creating static, animated, and interactive visualizations.

seaborn: For making statistical graphics.
