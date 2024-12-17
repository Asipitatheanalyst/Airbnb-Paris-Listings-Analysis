# Airbnb Listings Data Analysis Project

## Table Of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)

### Project Overview 
This project focuses on analyzing Airbnb listings data in Paris to uncover insights related to prices, neighborhoods, and host trends. The analysis involves data cleaning, preparation, and visualization to answer key questions such as:

- Which neighborhood in Paris has the highest average listing price?
- How do prices vary by accommodations?
- What trends exist in host activity over time?
- The project is divided into three main objectives:

1. Profiling and quality assurance (QA) of the data.
2. Data preparation for visualization.
3. Visualization and summarization of findings.

### Data Source
The dataset used for this analysis is provided by Maven Analytics as part of their guided projects. The data includes detailed Airbnb listing records for Paris, such as:

- Host information (e.g., host since year).
- Location details (e.g., neighborhood, city).
- Price and accommodations.

### Tools
- Python (Jupyter Notebook)
   - Libraries: pandas, numpy, matplotlib, seaborn
- Excel (optional for preliminary inspection)

### Data Cleaning
1. Import the Data: Load the listings.csv file into a Pandas DataFrame.
2. Cast Date Columns: Convert the host_since column to datetime format.
3. Filter Data: Focus only on Airbnb listings for Paris by filtering the city column.
4. Quality Assurance:
   - Check for and handle missing values.
   - Calculate descriptive statistics (minimum, maximum, and average) for numeric fields such as price.

### Exploratory Data Analysis
1. Average Price by Neighborhood: Grouped listings by neighborhood to compute mean prices.
2. Price by Accommodations:
   - Filtered data to focus on the most expensive neighborhood.
   - Grouped by the number of accommodations to compute mean prices.
3. Trends Over Time:
   - Grouped listings by the year hosts joined Airbnb (host_since).
   - Calculated the average price and number of new hosts for each year.

![Paris Accomodation](https://github.com/user-attachments/assets/156809d1-ac1b-4f4e-8ff1-528a98c62d99)

![Paris Neighbourhood](https://github.com/user-attachments/assets/dc76bfd4-45b5-4798-830c-2da01a56085f)

![New Airbnb Hosts](https://github.com/user-attachments/assets/24966fa0-c35f-4468-970f-8a6b6ec9b95f)

### Data Analysis
#### Key tasks performed during analysis:
1. Grouped Data:
   - Created aggregated tables to calculate average prices and host counts.
2. Visualized Insights:
   - Horizontal Bar Charts:
      - Average prices by neighborhood.
      - Average prices by accommodations in the most expensive neighborhood.
   - Line Charts:
      - Number of new hosts over time.
      - Average price trends over time.
3. Identified Key Metrics:
- Pinpointed the neighborhood with the highest average listing price.

### Results
- Neighborhood Insights:
   - The neighborhood with the highest average Airbnb listing price was identified.
- Accommodation Analysis:
   - Price trends by accommodations showed variability in cost based on property size and type.
- Trends Over Time:
   - Growth in new hosts was visualized alongside changes in average listing prices.

### Recommendations
- For Hosts:
   - Focus on the neighborhoods with higher demand and higher average prices for better profitability.
   - Adjust pricing strategies based on property size and accommodation type.
- For Airbnb Management:
   - Target areas with rapid host growth for promotional opportunities.
   - Monitor price trends to maintain competitiveness in the market.

### Limitations
- The analysis focuses solely on Paris listings, limiting generalizability to other locations.
- The dataset may lack up-to-date or seasonal pricing trends.
- Assumptions were made regarding missing values and outliers during QA.

### References
- Dataset provided by Maven Analytics.
- Tools and libraries: Python (pandas, matplotlib, seaborn).






