# Selenium-driven Data Harvesting and Sales Trends Analysis

## Overview
This project involves automating the download of sales data from a GitHub repository, performing data cleaning, analysis, and generating visualizations using Python. The analysis includes insights into monthly sales trends, the most sold products, the city with the highest sales, the best time to display advertisements, and products often sold together.

## Project Structure
The project is divided into several key steps:

### 1. Automating Downloads
- Selenium is used to navigate to a GitHub repository, search for specific files, and download them.
- Files for each month are downloaded and saved as individual CSV files.

### 2. Merging Monthly Reports
- The downloaded monthly CSV files are merged into a single file called `single_file.csv`.

### 3. Data Cleaning
- Identifying and handling missing values.
- Removing rows with special headers.
- Converting data types for analysis.

### 4. Data Analysis
#### Monthly Sales Analysis
- Analyzing and plotting monthly sales trends.
- Identifying the month with the highest sales.

#### City-wise Sales Analysis
- Analyzing and plotting sales data for different cities.
- Identifying the city with the highest sales.

#### Best Time to Display Advertisement
- Analyzing and plotting the number of orders at each hour.
- Identifying the best hour to display advertisements.

#### Products Analysis
- Analyzing and plotting the quantity ordered and average prices for each product.
- Identifying the top 3 most sold products and the least sold products.

#### Products Sold Together
- Finding products that are frequently sold together.

### 5. Visualization
- Visualizations are saved as PNG files for reference.
- Graphs include monthly sales, city-wise sales, advertisement display time, and product analysis.

### 6. Tabular Results
- Key metrics such as the month with the most sales, city with the highest sales, best time for advertisements, and product sales information are presented in a tabular format.

## Dependencies
- Python
- Selenium
- Pandas
- Matplotlib
- Tabulate

## Results
- The project provides insights into sales data trends, identifies top-selling products, and recommends optimal advertisement display times.
- Visualizations and tabular results are available for easy reference.

Feel free to explore the Jupyter notebook to delve deeper into the analysis and adapt the code for your own datasets. Contributions and feedback are welcome!
