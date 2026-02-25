# BlinkIT Grocery Data

## Overview

This dataset contains retail sales information from BlinkIT grocery outlets. The data includes product details, outlet information, and sales metrics used for analysis in the Power BI Blinkit project.

**File:** BlinkIT Grocery .xlsx

## Dataset Summary

- **Total Records:** 8,523 rows
- **Features:** 12 columns
- **Date Range:** Outlets established from 1999 onwards

## Column Descriptions

### Product Information

| Column | Data Type | Description |
|--------|-----------|-------------|
| **Item_Identifier** | String | Unique product identifier |
| **Item_Weight** | Float | Weight of the product (in appropriate units) |
| **Item_Fat_Content** | String | Fat content classification (Low Fat, Regular) |
| **Item_Type** | String | Category of the product (e.g., Dairy, Soft Drinks, Meat) |
| **Item_Visibility** | Float | Display visibility of the product in the outlet |
| **Item_MRP** | Float | Maximum Retail Price of the product |

### Outlet Information

| Column | Data Type | Description |
|--------|-----------|-------------|
| **Outlet_Identifier** | String | Unique outlet/store identifier |
| **Outlet_Establishment_Year** | Integer | Year the outlet was established |
| **Outlet_Type** | String | Type of outlet (e.g., Supermarket Type1, Supermarket Type2) |
| **Outlet_Size** | String | Size of the outlet (Small, Medium, High) |
| **Outlet_Location_Type** | String | Location tier of the outlet (Tier 1, Tier 2, Tier 3) |

### Sales Information

| Column | Data Type | Description |
|--------|-----------|-------------|
| **Item_Outlet_Sales** | Float | Sales revenue of the product at that outlet |

## Data Quality Notes

- Dataset contains both product and outlet dimensions
- Sales data covers multiple outlet locations across different tiers
- Products span various categories including Dairy, Soft Drinks, and Meat

## Usage

This data is used for:
- Sales analysis and forecasting
- Product performance evaluation
- Outlet profitability analysis
- Regional sales comparison
- Power BI dashboard creation

## Key Insights Available

- Identify best-selling products and categories
- Analyze outlet performance by location and type
- Evaluate product visibility impact on sales
- Compare sales across different outlet sizes and establishment years
