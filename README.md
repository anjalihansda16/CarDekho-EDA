
# Car Dekho Exploratory Data Analysis (EDA)

This project analyzes the CarDekho dataset to understand various factors influencing the selling price of used cars.

## Introduction

The CarDekho EDA project uses Python and libraries like Pandas, NumPy, Seaborn, and Missingno to explore and visualize the dataset.

## Dataset

The dataset contains information about used cars, including features like:

- **name**: Car model name
- **year**: Year of manufacture
- **selling_price**: Price at which the car was sold
- **km_driven**: Distance traveled by the car (in kilometers)
- **fuel**: Fuel type (e.g., Diesel, Petrol)
- **seller_type**: Type of seller (e.g., Individual, Dealer)
- **transmission**: Transmission type (e.g., Manual, Automatic)
- **owner**: Number of previous owners
- **mileage(km/ltr/kg)**: Mileage of the car (in km per liter or kg)
- **engine**: Engine capacity (in cc)
- **max_power**: Maximum power output (in bhp)
- **seats**: Number of seats

## Analysis Steps

1. **Understanding Data**: Checked dataset shape and information.
2. **Data Cleaning**:
- Converted columns to appropriate data types.
- Handled missing values using imputation.
- Removed duplicate entries.
- Used feature transformation for required columns. 
3. **Exploratory Data Analysis**:
- Analyzed distribution of numerical and categorical variables.
- Detected outliers and visualized them.
- Investigated correlations between numerical features.
- Visualized how categorical data has affected the selling price of used cars.
4. **Insights**:
   - Found strong correlation between 'selling_price' and 'max_power', 'engine'.
   - Noted differences in selling price based on fuel type, transmission, and ownership history.

## Conclusion

The analysis provides valuable insights into the used car market, helping in understanding how various factors affect the selling price. Further analysis and modeling could be done for accurate price predictions.

