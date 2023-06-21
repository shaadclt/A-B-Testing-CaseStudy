## A/B Testing Analysis

This code performs an A/B testing analysis using control and test group data. It analyzes various metrics such as amount spent, number of impressions, reach, website clicks, searches received, content viewed, added to cart, and purchases. The analysis includes visualizations of the data using Plotly.

### Dependencies

This code requires the following libraries:

- pandas
- datetime
- plotly.graph_objects
- plotly.express
- plotly.io

Please make sure to install these dependencies before running the code.

### Data Files

This code assumes the existence of two CSV files:

- `control_group.csv`: Contains data for the control group.
- `test_group.csv`: Contains data for the test group.

Please make sure to place these files in the same directory as the code.

### Usage

1. Ensure that the required dependencies are installed.
2. Place the `control_group.csv` and `test_group.csv` files in the same directory as the code.
3. Run the code in a Python environment.
4. The code will load and preprocess the data, perform the analysis, and generate visualizations using Plotly.
5. The visualizations will be displayed interactively in separate windows.

### Results

The code generates the following visualizations:

1. Scatter plot: Amount Spent vs. Number of Impressions, with trendlines for different campaign names.
2. Pie chart: Total Searches from Control Campaign vs. Test Campaign.
3. Pie chart: Website Clicks from Control Campaign vs. Test Campaign.
4. Pie chart: Content Viewed from Control Campaign vs. Test Campaign.
5. Pie chart: Products Added to Cart from Control Campaign vs. Test Campaign.
6. Pie chart: Amount Spent in Control Campaign vs. Test Campaign.
7. Pie chart: Purchases Made by Control Campaign vs. Test Campaign.
8. Scatter plot: Content Viewed vs. Website Clicks, with trendlines for different campaign names.
9. Scatter plot: Added to Cart vs. Content Viewed, with trendlines for different campaign names.
10. Scatter plot: Purchases vs. Added to Cart, with trendlines for different campaign names.

Please refer to the generated visualizations for a detailed analysis of the A/B testing results.

### Acknowledgments

This code uses the Plotly library for data visualization.
