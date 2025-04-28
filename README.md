# PriceEvolutionOverTime


## Overview

This dataset contains pricing information for various meat, poultry, and dairy products in Province 1 for the month of January 2017. It includes details such as product type, category, unit price, whether the item is essential or non-essential, and product descriptions. The data is structured to provide insights into average product prices and their classification.

## Dataset Details

- **Columns:**
  - `Year`: Year of data entry (e.g., 2017).
  - `Month`: Month of data entry (e.g., January).
  - `Province`: Province where the pricing is applicable (e.g., Province 1).
  - `Category`: The product category (e.g., Meat & Poultry, Dairy & Eggs).
  - `Product`: The name of the product (e.g., Beef stewing cuts, Whole chicken, Milk).
  - `Unit_Price`: The price per unit of the product (e.g., $12.66).
  - `Discount`: Whether the product is discounted or not (Yes/No).
  - `Quantity`: Number of products listed in the dataset (usually 11 per entry).
  - `Total_Price`: Total price for the quantity of the product (same as `Unit_Price` for each entry).
  - `Essential_NonEssential`: Whether the product is classified as essential or non-essential.
  - `Rating`: Product rating (e.g., 11.1, 11.2).
  - `Currency`: The currency of the price listed (e.g., Dollars).

## Data Example

| Year | Month  | Province  | Category     | Product                     | Unit_Price | Discount | Quantity | Total_Price | Essential_NonEssential | Rating | Currency |
|------|--------|-----------|--------------|-----------------------------|------------|----------|----------|-------------|------------------------|--------|----------|
| 2017 | January| Province 1| Meat & Poultry| Beef stewing cuts, per kilogram | 12.66      | No       | 11       | 12.66       | Essential              | 11.1   | Dollars  |
| 2017 | January| Province 1| Meat & Poultry| Beef striploin cuts, per kilogram | 21.94    | No       | 11       | 21.94       | Essential              | 11.2   | Dollars  |
| 2017 | January| Province 1| Dairy & Eggs | Milk, 1 litre                | 2.17       | No       | 11       | 2.17        | Essential              | 11.13  | Dollars  |

## Features

- **Product Categories:** The dataset covers a wide range of categories, such as:
  - Meat & Poultry
  - Dairy & Eggs
- **Price Information:** For each product, the unit price, total price, and whether the product is discounted or not are recorded.
- **Essential vs Non-Essential:** Each product is classified as either "Essential" or "Non-Essential" based on its nature and necessity.
- **Product Ratings:** A numeric rating is assigned to each product, although its specific meaning or scale is not explained.

## Usage

This dataset can be used for various analyses and visualizations, such as:
- **Price Comparisons:** Comparing prices across different products and categories.
- **Essential vs Non-Essential:** Analyzing the price distribution of essential and non-essential items.
- **Product Insights:** Understanding which products are most frequently purchased or priced higher.

## Data Source

This dataset was manually created for the purposes of analysis and is fictional in nature. It can be used for exploring pricing trends, consumer behavior, or for practice in data analysis tasks.

## Example Use Cases

- **Exploratory Data Analysis (EDA)**: Perform statistical analysis to find correlations between product prices and their essential/non-essential classification.
- **Price Distribution**: Visualize the distribution of prices across different product categories.
- **Trend Analysis**: Analyze changes in prices over time or across product categories (though this dataset only contains data for January 2017).

## Requirements

To work with this dataset, ensure you have the following Python packages installed:
- `pandas` for data manipulation
- `matplotlib` and `seaborn` for data visualization

You can install these dependencies with:

```bash
pip install pandas matplotlib seaborn
