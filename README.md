# Analyzing Online Sports Revenue

## Project Description
This project analyzes product data from an online sports retail company to explore revenue trends and product ratings. The analysis demonstrates **exploratory data analysis (EDA), data cleaning, merging datasets, and feature engineering** to extract actionable insights.

## Data
The project uses four CSV files:

- `Analyzing_Online_Sports_Revenue.ipynb` – The main notebook containing all analysis and code. 
- `brands.csv` – Brand of each product
- `finance.csv` – Product prices, discounts, and revenue  
- `info.csv` – Product names and descriptions  
- `reviews.csv` – Product ratings and number of reviews  

## Data Processing
- Datasets were loaded using Python (`pandas`).  
- Datasets were merged on `product_id` and null values were removed.  
- A `price_label` column was added based on `listing_price` quartiles.  
- `description_length` was computed and categorized into 100-character bins.  

## Key Findings
- **Adidas Elite products** generate the highest average revenue.  
- Longer product descriptions do **not always correlate with higher ratings**.  
- Most products fall in mid-price categories (`Average` and `Expensive`).  

## How to Reproduce
1. Install Python (3.8+) and `pandas`.  
2. Place all CSV files in the project directory.  
3. Run the notebook to reproduce the analysis and tables.
