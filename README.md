# COVID-19 Data Analysis and Visualization

This project analyzes and visualizes global COVID-19 data to uncover trends, correlations, and insights. It uses data from the `owid-covid-data.csv` file to explore cases, deaths, and vaccination rates across different countries.

## Objectives

1. Clean and preprocess COVID-19 data for analysis.
2. Visualize trends in total cases, deaths, and vaccination rates over time.
3. Compare COVID-19 statistics between selected countries.
4. Generate a correlation heatmap to identify relationships between numeric features.
5. Create a choropleth map to visualize global COVID-19 case density.

## Tools and Libraries Used

- **Python**: Programming language used for data analysis and visualization.
- **Pandas**: For data manipulation and preprocessing.
- **Matplotlib**: This is used to create static visualizations.
- **Seaborn**: For advanced statistical visualizations.
- **Plotly**: For interactive visualizations, including the choropleth map.
- **OS**: For file handling and directory management.

## How to Run/View the Project

1. Ensure you have Python installed on your system.
2. Install the required libraries using the following command:
   ```sh
   pip install pandas matplotlib seaborn plotly
   ```
3. Place the `owid-covid-data.csv` file in the same directory as `load_data.py`.
4. Run the script using:
   ```sh
   python load_data.py
   ```
5. The script will generate various plots and an interactive choropleth map.

## Insights and Reflections

- The death rate varies significantly between countries, highlighting the importance of healthcare infrastructure.
- Vaccination rates are unevenly distributed, with some countries achieving high coverage while others lag.
- The correlation heatmap reveals strong relationships between certain features, such as total_cases and total_deaths.
- Interactive visualizations like the choropleth map provide a global perspective on the pandemic's impact.

This project demonstrates the power of data visualization in understanding complex datasets and deriving actionable insights.
```
