# Business Visit Frequency Analysis

This project analyzes the business visit frequency of customers who accept coupons for different types of businesses. It uses a dataset that includes information on how often customers visit various types of businesses and whether they accepted a coupon.

## Dataset

The dataset contains the following columns:
- `Y`: Indicates whether the coupon was accepted (1) or not (0).
- `coupon`: The type of coupon offered.
- `CarryAway`: Frequency of visits to carry-away restaurants.
- `RestaurantLessThan20`: Frequency of visits to restaurants with meals costing less than $20.
- `Restaurant20To50`: Frequency of visits to restaurants with meals costing between $20 and $50.
- `Bar`: Frequency of visits to bars.
- `CoffeeHouse`: Frequency of visits to coffee houses.

## Analysis

The analysis involves the following steps:
1. **Data Preprocessing**:
    - Mapping categorical frequency data to numerical values for correlation analysis.
    - Replacing coupon and business names for better visualization.
2. **Visualization**:
    - Creating bar plots to show the distribution of visits for each business type.
    - Annotating bars with the percentage of total visits for each category.
    - Using pie charts to visualize the acceptance rate of coupons for different temperatures.

## Requirements

The following Python libraries are required for the analysis:
- pandas
- seaborn
- matplotlib

## Usage

To run the analysis, execute the provided Jupyter Notebook (`analysis.ipynb`). The notebook includes all necessary steps for preprocessing the data, creating visualizations, and calculating statistics.

## File Description

- `analysis.ipynb`: Jupyter Notebook containing the complete analysis workflow.
- `README.md`: This README file.

## Visualizations

### Bar Plots
The bar plots show the distribution of visits for each business type, with bars annotated to indicate the percentage contribution of each category to the total count.

### Pie Charts
The pie charts display the percentage of participants who accepted the coupon at different temperature ranges.

## Results

The analysis provides insights into the characteristics of customers who accept coupons and their business visit frequencies. The visualizations help identify patterns and correlations between business visit frequency and coupon acceptance.

## Future Work

Further analysis can be conducted to explore other factors influencing coupon acceptance, such as age, gender, and marital status.

## Contact

For any questions or inquiries, please contact Niccolò Meniconi at nic.meniconi@gmail.com


