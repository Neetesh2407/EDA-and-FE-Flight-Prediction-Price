
# Flight Price Prediction: EDA & Feature Engineering

This project aims to perform comprehensive Exploratory Data Analysis (EDA) and Feature Engineering (FE) on a flight price dataset to understand the factors influencing flight prices and prepare the data for predictive modeling.

## Overview

The dataset used for this project includes various details related to flights, such as departure time, arrival time, duration, airline, and ticket prices. The primary goal is to identify key insights and trends through EDA and then enhance the dataset through Feature Engineering to improve the accuracy of flight price prediction models.

## Dataset

- **Source**: [Flight Price Dataset](#)
- **Description**: The dataset includes features like airline, flight duration, number of stops, departure and arrival times, and ticket prices.

## Features

Key features of the dataset include:
- **Airline**: Name of the airline.
- **Departure Time**: Scheduled departure time of the flight.
- **Arrival Time**: Scheduled arrival time of the flight.
- **Duration**: Total flight duration.
- **Total Stops**: Number of stops during the flight.
- **Price**: Ticket price of the flight.

## Analysis Performed

### Exploratory Data Analysis (EDA):
1. **Data Cleaning**:
   - Removal of missing values.
   - Standardization of time formats and other categorical variables.
   - Handling of outliers in price and duration columns.

2. **Data Visualization**:
   - Distribution of flight prices based on airlines.
   - Influence of total stops on flight prices.
   - Effect of flight duration on price trends.
   - Correlation matrix to explore relationships between features.

### Feature Engineering (FE):
1. **Date and Time Features**:
   - Extracted hour, day, and month from departure and arrival times.
   - Created new features based on time of day (morning, evening, night).

2. **Handling Categorical Data**:
   - Converted categorical columns like airline and stops into numerical values using encoding techniques.

3. **Flight Duration Analysis**:
   - Transformed the flight duration feature into a more predictive format by separating hours and minutes.

## Tools & Libraries

- **Python**: Main language used for analysis.
- **Pandas**: For data manipulation and cleaning.
- **NumPy**: For numerical computations.
- **Matplotlib** & **Seaborn**: For visualizing trends and relationships.
- **Scikit-learn**: For feature engineering and preparing data for modeling.

## Usage

To run the project, clone the repository and install the required libraries:

```bash
git clone https://github.com/Neetesh2407/EDA-and-FE-Flight-Prediction-Price.git
cd EDA-and-FE-Flight-Prediction-Price
pip install -r requirements.txt
```

After installing the dependencies, you can explore the analysis through the Jupyter Notebook:

```bash
jupyter notebook Flight_Price_EDA_FE.ipynb
```

## Conclusion

Through EDA, we have uncovered significant insights into the factors that affect flight prices, such as the number of stops and airline choice. Feature Engineering has helped us transform the dataset into a more usable format for machine learning models, setting the stage for effective flight price prediction.

## Future Work

- Implement various machine learning models for flight price prediction.
- Perform hyperparameter tuning to improve model accuracy.
- Experiment with advanced feature engineering techniques.

## Author

- **Neetesh Kumar** - Data Scientist
