# World Bank Data Visualisation

## Objective:
The primary objective of this project is to analyze and visualize World Bank data using the Pandas library in Python. The World Bank provides a wealth of socio-economic indicators for countries around the globe, and this project aims to create meaningful visualizations to gain insights into global trends and patterns.

## Technologies Used:
* Python: Utilize Python programming language for data manipulation, analysis, and visualization.
* Pandas: Leverage the Pandas library for data cleaning and analysis.
* Matplotlib and Seaborn: Use these libraries for static visualizations.
* Plotly: Employ Plotly for interactive and dynamic visualizations.
* Jupyter Notebooks: Develop and present the analysis in Jupyter Notebooks for a more interactive and user-friendly experience.

## Dataset Information:
* Life expectancy at birth: The number of years a newborn would live if the patterns of mortality at the time of birth remain the same throughout his life.
* Fertility rate: Number of children a woman would give birth to during her childbearing years.
* Country population: Total number of residents regardless of legal status or citizenship (midyear estimates).
  
Hans Rosling built this animation, after testing his students on global health, he realized that they still thought that the world was divided in two:
* The Western world: low fertility rate and high life expectancy.
* The third world: high fertility rate and low life expectancy.
  
The following steps were performed to build animated visualization: 
1. Load Data
2. Data Overview
3. Handle Missing Values
4. Data Types
5. Merge DataFrames (If required for any visualization).

The visualization graph made is: 
* Population Trends (Years vs Population)(Line Graph)
* Fertility rate distribution 
* Life expectancy variation
* Correlation Analysis
* Regional Analysis





Hint: 
1. Load all three datasets 
2. Data preprocessing on each dataset
3. Use the Pandas dataset merge method (DataFrame.merge) to combine the 3 datasets
4. Create a list of continents with their counties and then use if else to create a new column for each continent. 
