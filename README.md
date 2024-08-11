# Exploratory Analysis 
## Data Cleaning & Cleaning

- Data Merging: The dataset was split due to varying variables over time (2015-2016 and 2017-2024) and was merged after standardizing columns. A new column for remaining lease was calculated and added back to the dataset.
- Date Formatting: The month column was converted to Date format for better plotting. A “Year” column was added for clarity.
- Consistency Checks: Flat model names were standardized to lowercase for consistency, and the storey range format was unified.
- Geospatial Mapping: Town locations in Singapore were plotted using ggmap, with longitude and latitude converted to numeric. The town names were standardized to lowercase for seamless merging.
- Visualization
Four maps were generated to visualize the evolution of resale prices across different locations in Singapore over time.
This dataset is now optimized for detailed analysis and visualization, providing a solid foundation for exploring trends in HDB resale prices.
