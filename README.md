# flipkart-moblie-analysis
Flipkart Mobile Data Analysis using Python, Pandas, NumPy, and Matplotlib with API data, brand-wise pricing, discount analysis, product ratings, and visualizations.
# Flipkart Mobile Data Analysis using Python

## Project Overview
This project analyzes mobile product data retrieved through the QuickCommerce API using the Flipkart platform parameter. The analysis focuses on product brands, pricing, discounts, customer ratings, and mobile price ranges using Python data analysis and visualization libraries.

## Objectives
- Retrieve mobile product data from an API.
- Explore and inspect product data using Pandas.
- Analyze product counts and average prices by brand.
- Calculate discount percentages using MRP and offer price.
- Explore product ratings and rating counts.
- Categorize mobile phones into price ranges.
- Create charts to visualize pricing and discount patterns.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Requests
- Google Colab
- QuickCommerce API

## Analysis Performed

### 1. API Data Collection
Retrieved mobile product data from the QuickCommerce API using the Flipkart platform parameter and converted the JSON response into a Pandas DataFrame.

### 2. Data Exploration
- Inspected column names, data types, and dataset dimensions.
- Viewed sample product records.
- Generated descriptive statistics.

### 3. Brand Analysis
- Counted products for each brand.
- Calculated average prices by brand.
- Visualized brand-wise product counts.

### 4. Discount Analysis
Calculated discount percentage using the formula:

`Discount (%) = ((MRP - Offer Price) / MRP) * 100`

Compared discounts across brands and visualized average discount percentages.

### 5. Price Analysis
- Compared MRP with offer price.
- Identified products with offer prices below ₹15,000 and ₹20,000.
- Calculated average offer price by brand.
- Grouped products into Low Range, Mid Range, and High Range categories.

### 6. Rating Analysis
- Filtered products with ratings above 4.
- Examined rating counts.
- Identified highly rated products with higher rating counts.
- Visualized the relationship between offer price and product rating.

## Visualizations
The project includes:
- Brand-wise product count bar chart
- Average offer price by brand
- Average discount by brand
- MRP vs. offer price scatter plot
- Product rating vs. offer price scatter plot
- Mobile count by price range

## Key Skills Demonstrated
- API data extraction
- DataFrame creation and exploration
- Data filtering and sorting
- GroupBy aggregation
- Discount calculation
- NumPy array filtering
- Data visualization
- Exploratory Data Analysis (EDA)

## How to Run the Project

1. Download or clone this repository.
2. Open `flipkart_py.ipynb` in Google Colab.
3. Obtain an API key from the relevant API provider.
4. Run the notebook cells in order.
5. Enter your API key when prompted.
6. Review the analysis results and visualizations.

**Important:** API access, credits, and product availability depend on the API provider. The notebook retrieves data at runtime, so the results may change between runs.

## Conclusion
This project demonstrates how Python can be used to collect and analyze mobile product data, compare brand-wise pricing, calculate discounts, explore ratings, and communicate findings through visualizations. It provides practical experience in API integration and exploratory data analysis for an entry-level Data Analyst portfolio.

## Author
Bharanidharan V

**Tools:** Python | Pandas | NumPy | Matplotlib | Requests
