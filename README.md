**BDA 594 Final Project**

# Supply and Demand of EV Charging Stations in Relation to EV Population in Washington State

## Project Overview

This project aims to analyze the supply and demand dynamics of Electric Vehicle (EV) charging stations in relation to the EV population in Washington State. The study explores the correlation between the number of charging stations, EV population, and demographic factors such as median income and education levels. The goal is to identify areas where the supply of charging stations may not meet the demand and to predict future trends in EV adoption and charging infrastructure needs.

## Team Members

- **Anastasia Kurakova**: Data Preprocessing, Tableau Visualization, Website
- **Sabnam Pandit**: Exploratory Data Analysis, Machine Learning Models, Website
- **FNU Dipsy**: Time Series Analysis, Video
- **Timothy Boyd**: ArcGIS Visualization Analysis, Video

## Project Components

### 1. Data Sources
- **Electric Vehicle Population Data**: [EV-Data Link](https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2/about_data)
- **Alternative Fuel Stations Data**: [Charging Stations - Data Link](https://afdc.energy.gov/data)
- **American Community Survey (2021)**: [Census Data: Education and Income - Data Link](https://www.census.gov/data.html)
- **Crosswalk from ZCTA to Zip Code Database**: [Crosswalk Database Link](https://udsmapper.org/zip-code-to-zcta-crosswalk/)

### 2. Tools and Techniques
- **Data Preprocessing**: Microsoft Excel, Python (pandas, sci-kit learn)
- **Exploratory Data Analysis**: Tableau, Pandas
- **Machine Learning Models**: Random Forest Regressor, Gradient Boosting Regressor, Linear Regression, Support Vector Regression
- **Time Series Analysis**: ARIMA Model, Polynomial Regression
- **Geospatial Visualization**: ArcGIS

### 3. Key Findings
- **EV Population Distribution**: The majority of EVs are concentrated in the Greater Seattle area, with Tesla being the leading manufacturer.
- **Charging Station Distribution**: Charging stations are predominantly located in areas with high EV populations, particularly in urban centers.
- **Correlation Analysis**: A strong positive correlation was found between the number of EVs and the number of charging stations. Education levels also showed a moderate correlation with EV adoption and charging station availability.
- **Future Predictions**: The ARIMA model forecasts a steady increase in both EV population and charging station numbers over the next five years.

### 4. Machine Learning Models
- **Gradient Boosting Regressor** and **Random Forest Regressor** performed the best in predicting the number of charging stations based on EV population, median income, and education levels.
- **EV Count** was identified as the most significant predictor of charging station availability.

### 5. Data Visualization
- **Tableau**: Used for initial exploratory data analysis and visualization of EV population and charging station distribution.
- **ArcGIS**: Utilized for geospatial visualization, including EV hotspots, charging station buffers, and education level overlays.

### Project Website: Visit the Website [Link](https://sites.google.com/sdsu.edu/ev-chargingstations/home?authuser=1)
