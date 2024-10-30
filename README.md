# Bike Sharing Demand Prediction
> This project aims to build a predictive model to forecast daily bike-sharing demand based on various factors like temperature, weather, holidays, and seasons.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## General Information
- This project addresses the problem of forecasting bike demand for a bike-sharing company, which can improve planning, staffing, and resource allocation.
- The company faced significant drops in demand due to the COVID-19 pandemic and now wants to understand which factors drive bike usage to better serve post-pandemic demand.
- By accurately predicting demand, the company can optimize bike availability, reducing customer wait times and improving user satisfaction.
- **Dataset**: The dataset used includes daily bike demand records, including features such as temperature, humidity, wind speed, season, weather conditions, and holiday indicators.

## Conclusions
- **Temperature and Feeling Temperature (atemp)**: These factors show the strongest positive correlation with bike demand, suggesting that warmer weather increases bike rentals.
- **Seasonal Impact**: Demand tends to be higher in warmer seasons like Summer and Fall.
- **Weather Conditions**: Clear weather encourages bike usage, while rain and snow reduce demand.
- **Model Performance**: A linear regression model achieved an R-squared score of approximately 0.84 on the test set, indicating a good fit for predicting bike-sharing demand.

## Technologies Used
- Python 3.8
- pandas - version 1.2.0
- numpy - version 1.19.5
- seaborn - version 0.11.1
- matplotlib - version 3.3.3
- scikit-learn - version 0.24.1

## Acknowledgements
- This project was inspired by data science coursework focused on predictive modeling.
- Dataset source: Fanaee-T, Hadi, and Gama, Joao, "Event labeling combining ensemble detectors and background knowledge," *Progress in Artificial Intelligence*, Springer Berlin Heidelberg, doi:10.1007/s13748-013-0040-3.
- Special thanks to open-source contributors of Python libraries used in this project.

## Contact
Created by [@Sharavanakumar35](https://github.com/Sharavanakumar35) - feel free to contact me!
