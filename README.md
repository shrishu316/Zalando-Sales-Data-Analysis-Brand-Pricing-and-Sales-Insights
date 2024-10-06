# Zalando Product Dataset Analysis

## Overview
This project focuses on analyzing the **Zalando Product Dataset** to explore pricing trends, brand performance, and sales distribution. Key figures, visualizations, and statistical methods were applied to extract insights from the data.

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

## Statistical Tests
- **ANOVA Test:** Detected significant price differences among brands.
- **Tukey HSD Test:** Post-hoc comparison between brand prices.

## How to Use
1. Install necessary dependencies:
   ```bash
   pip install pandas matplotlib seaborn scipy statsmodels

## Visualizations
### Price Distribution
![Price Distribution in Bekleidung Category](https://github.com/user-attachments/assets/7bb811b0-4aa2-409f-8f20-700b98e746ef)

### Top 10 Selling Brands
![Top Ten Selling Brands](https://github.com/user-attachments/assets/25bb2309-bedc-4a6e-9bd0-d3d225428723)

### Least 10 Selling Brands
![Least Ten Selling Brands](https://github.com/user-attachments/assets/6dfd5d4d-dc0c-40cb-80e1-a20ffeb33afe)

### Average Price of Top Ten Brands
![Average Price of Top Ten Brands](https://github.com/user-attachments/assets/8235c87a-9763-40da-b605-d6ffa75d45fc)

### Average Price of Least Ten Brands
![Average Price of Least Ten Brands](https://github.com/user-attachments/assets/f88c4745-3c4a-4413-99e7-fc07bbd9dfa8)

### Sales Volume by Price Range
![Sales Volume by Price Range](https://github.com/user-attachments/assets/4d2d8cae-f9c2-4105-a221-42f3ecc8f9f9)

### Average Price by Selected Brands in Bekleidung Category
![Average Price by Selected Brands in Bekleidung Category](https://github.com/user-attachments/assets/1cb790ca-5464-4506-9587-50b14c2838f1)

### Price Distribution for Selected Brands
![Price Distribution for Selected Brands](https://github.com/user-attachments/assets/ed7b5c7a-cff3-433c-bcce-2fe615ae1465)

