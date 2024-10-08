#  Analysis 
## Data Cleaning & Cleaning

- Data Merging: The dataset was split due to varying variables over time (2015-2016 and 2017-2024) and was merged after standardizing columns. A new column for remaining lease was calculated and added back to the dataset.
- Date Formatting: The month column was converted to Date format for better plotting. A “Year” column was added for clarity.
- Consistency Checks: Flat model names were standardized to lowercase for consistency, and the storey range format was unified.
- Geospatial Mapping: Town locations in Singapore were plotted using ggmap, with longitude and latitude converted to numeric. The town names were standardized to lowercase for seamless merging.
- Visualization
Four maps were generated to visualize the evolution of resale prices across different locations in Singapore over time.
This dataset is now optimized for detailed analysis and visualization, providing a solid foundation for exploring trends in HDB resale prices and is shown below.

![Screenshot 2024-08-11 163105](https://github.com/user-attachments/assets/d966b7eb-591c-4344-aa7d-7928f65a4180)


# Exploratory Analysis
## Line Plot of Resale Market and GDP
- The graph below shows the trend and increase in HDB resale prices and GDP per capita of Singapore over the years.
- A correlation can be seen as both graphs are on an upward trend

![Screenshot 2024-08-16 175400](https://github.com/user-attachments/assets/3ae2bebb-32ac-44bb-9667-f9be3d6de174)

![Screenshot 2024-08-16 175406](https://github.com/user-attachments/assets/43abcdee-ce65-406e-972c-4efdc5c27b89)


## Bar plot of Flats sold by Flat Type and Average price of HDB Models
- The average price of types HDB models can be seen below with Type S2 being the most expensive model. The different layout or corner units can often fetch an increased price and investors or buyers should evaluate the differences before making any decsions. 
- From the graph below, different kinds of number of HDB flat models sold can be seen and is ranked by popularity. 4 room and 3 room flats are in the most demand over the years.

![Screenshot 2024-08-16 175417](https://github.com/user-attachments/assets/854cc3c9-4b9a-4b93-b6e1-056f227ac75d)

![Screenshot 2024-08-16 175428](https://github.com/user-attachments/assets/654406ca-6824-4dc1-a99e-0ff00d3017a7)


## Map Plot from 1990-2024

- Urbanisation can be seen as people started moving into the the central area of Singapore. Massive growth of singapore can be seen and the prices reflect these changes.
- Demand for HDB in these areas can be seen as economic opportunites in these areas were growing

![Screenshot 2024-08-16 175437](https://github.com/user-attachments/assets/ff614a94-cce1-40a8-82e5-861610a5a4eb)

![Screenshot 2024-08-16 175442](https://github.com/user-attachments/assets/9d2759fc-e32b-4f21-bad5-4cdd3c2a585c)

![Screenshot 2024-08-16 175446](https://github.com/user-attachments/assets/683f7cfb-ef0e-4067-9b35-6de927d31a87)

![Screenshot 2024-08-16 175450](https://github.com/user-attachments/assets/08807a0f-6264-45d1-8c47-9d827d2a0e7c)


# Conclusion
Key findings from the analysis found that there are many variables to consider that can influence resale prices. Factors such as income and GDP play a massive role in the housing market. The different types of HDBs sold, which flat type has the most demand all influence the HDB prices. The maps highlighted the differences in pricing in areas as urbanisation took place. Location being a massive factor in which the prices were affected can also be seen in the graphs. These graphs provided an overview of the variables and observations of the dataset. All these factors influence the pricing of the HDB resale price and have been explored by the graphs above. Understanding these variables sets the stage for further analysis and key data insights can be explored from it. By cleaning the data, inconsistencies and errors were addressed for the dataset’s reliability. Buyers and investors could use this visualization and make informed decisions when purchasing a unit.
