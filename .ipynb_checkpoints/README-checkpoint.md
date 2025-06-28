# Car Prices Analysis Project

## Project Overview
This project analyzes a dataset of used car sales to uncover insights about pricing trends, vehicle characteristics, and market dynamics. The dataset contains detailed information about various cars sold at auction, including their make, model, year, condition, mileage, and sale price.

## Dataset Description
The dataset `car_prices.csv` contains the following columns:

- **year**: Model year of the vehicle
- **make**: Manufacturer/brand of the vehicle
- **model**: Specific model name
- **trim**: Trim level/variant
- **body**: Body type (Sedan, SUV, etc.)
- **transmission**: Transmission type (automatic/manual)
- **vin**: Vehicle Identification Number
- **state**: State where sold (all CA in this dataset)
- **condition**: Vehicle condition rating (1-5 scale, with some missing values)
- **odometer**: Mileage at time of sale
- **color**: Exterior color
- **interior**: Interior color
- **seller**: Company that sold the vehicle
- **mmr**: Manheim Market Report price (estimated market value)
- **sellingprice**: Actual sale price
- **saledate**: Date and time of sale

The dataset contains 558837 records of vehicles sold primarily in California between December 2014 and February 2015, with model years ranging from 2013-2015.

## How to Navigate the Project

### Data Exploration
1. **Initial Exploration**: Examining the structure of the dataset, check for missing values, and understand the distribution of key variables.
2. **Descriptive Statistics**: Calculation of summary statistics for numerical columns (price, mileage, year).
3. **Visualizations**: Creating charts to visualize relationships between variables (price vs. mileage, price by make/model).

### Analysis Focus Areas
1. **Price Analysis**:
   - Compare selling price to MMR (Manheim Market Report) values
   - Identify makes/models with the highest/lowest prices
   - Analyze how mileage affects price

2. **Vehicle Characteristics**:
   - Most common makes/models in the dataset
   - Price differences between body types
   - Transmission type impact on price

3. **Temporal Analysis**:
   - Price trends over the sales period (Dec 2014-Feb 2015)
   - Seasonal effects on pricing

### Data Cleaning Notes
The dataset appears to be already cleaned with:
- Consistent formatting
- Standardized column names
- No obvious duplicates
- Missing values are minimal and represented consistently

## Getting Started
1. We load the dataset into our preferred analysis tool (Python Jupyter Notebook)
2. we begin with exploratory analysis to Understand more more about the data
3. We Formulate specific questions to investigate based on first findings

## Potential Extensions
- Compare prices across different vehicle segments
- Analyze depreciation rates by make/model
- Investigate the relationship between vehicle condition and sale price
- Identify any particularly good or bad deals (sellingprice vs mmr)
