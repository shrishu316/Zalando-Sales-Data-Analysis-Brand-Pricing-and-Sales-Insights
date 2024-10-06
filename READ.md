# Zalando Product Dataset Analysis

## Overview
This project focuses on analyzing the **Zalando Product Dataset** to explore pricing trends, brand performance, and sales distribution. Key figures, visualizations, and statistical methods were applied to extract insights from the data.

## Visualizations
### Price Distribution
![Price Distribution in Bekleidung Category](https://github.com/user-attachments/assets/7bb811b0-4aa2-409f-8f20-700b98e746ef)

### Top 10 Selling Brands
![Top Ten Selling Brands](https://github.com/user-attachments/assets/25bb2309-bedc-4a6e-9bd0-d3d225428723)

### Least 10 Selling Brands
![Least Ten Selling Brands](https://github.com/user-attachments/assets/6dfd5d4d-dc0c-40cb-80e1-a20ffeb33afe)

## Dataset
- **Source:** [Zalando Product Dataset on Kaggle](https://www.kaggle.com/datasets/polartech/zalando-product-dataset)
- **Key Columns:**
  - `PRICE_CURRENT`: Product price
  - `BRAND`: Product brand
  - `CATEGORY`: Product category
  - `GENDER`: Gender target
  - `SCAN_DATE`: Date of price scan

## Data Preprocessing
1. Removed unnecessary columns like `SKU_VARIANT`, `PROMOTION`.
2. Handled missing data in `PRICE_LABEL` and standardized `CATEGORY`.
3. Converted `SCAN_DATE` to `datetime` and extracted year/month.

## Key Figures
- **Top Brands:** Analysis of top 10 brands by total sales.
- **Price Segmentation:** Grouped products into Low, Medium, and High price ranges.
- **Brand Price Analysis:** Comparison of average prices across selected brands.

## Statistical Tests
- **ANOVA Test:** Detected significant price differences among brands.
- **Tukey HSD Test:** Post-hoc comparison between brand prices.

## How to Use
1. Install necessary dependencies:
   ```bash
   pip install pandas matplotlib seaborn scipy statsmodels
