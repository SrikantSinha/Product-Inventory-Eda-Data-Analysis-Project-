# Product Dataset – Exploratory Data Analysis (EDA)

## Project Overview
This project performs a comprehensive exploratory data analysis on a product dataset containing 1,000 entries with attributes like price, stock levels, categories, brands, and availability. The primary goal was to clean raw data and uncover key relationships between pricing and inventory to help understand product assortment performance.

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## Key Analysis & Features
* **Data Cleaning:** Handled missing values by replacing them with the median, standardized column names, and corrected data types (e.g., EAN as string to prevent scientific notation).
* **Feature Engineering:** Created a custom `is_available` boolean feature based on product availability status (In Stock vs. Backorder/Pre-order).
* **Visualizations:**
    * Distribution of price and stock levels.
    * Concentration analysis for Top Brands and Categories.
    * Scatter plots to test the correlation between price and stock.

## Key Insights
* **Inventory Concentration:** A handful of categories (like "Books & Stationery") and brands dominate the product assortment.
* **Price vs. Stock:** There is no meaningful correlation between a product's price and its stock quantity, indicating that high-value items are not necessarily kept in lower quantities.
* **Assortment Variability:** The dataset shows high variability in both cost and inventory, suggesting a diverse product range with several outliers.

## How to Run
1. Clone this repository.
2. Ensure you have the dependencies installed: `pip install pandas numpy matplotlib seaborn`.
3. Open `main.ipynb` in Jupyter Notebook or VS Code.
