# California Housing Prices Prediction App

![animated](https://user-images.githubusercontent.com/69912320/234723379-21eab3af-67c2-45e7-97d1-19613de4cfc0.gif)

## Web app: [https://housepricecalifornia-clark-university.streamlit.app/](https://housepricecalifornia-clark-university.streamlit.app/)

## 🔍 About the project

In this project, we'll employ linear regression techniques with the **scikit-learn** library in **Python** to predict housing prices in California. The aim is to understand which characteristics of a residential property (such as number of rooms, location, local income, etc.) influence its market value.

The dataset used was [obtained from Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices) and pertains to the **1990 census**. We'll utilize data cleaning and preprocessing techniques to prepare them for analysis.

Next, we'll employ **linear regression** to model the relationship between house characteristics and their market price. To evaluate the model's quality, we'll use metrics like **R²** and **RMSE**.

Finally, a web application was created using **Streamlit**, where users can predict the value of a property based on provided data. We'll analyze the results and understand the project's business perspective, potentially aiding real estate professionals, investors, and even individuals in search of a home to purchase.

## Data Description

The dataset contains the following variables:

- **`longitude`**: Longitude of a specific set of houses.
- **`latitude`**: Latitude of a specific set of houses.
- **`housing_median_age`**: Median age of houses in a block.
- **`total_rooms`**: Total number of rooms in a housing block.
- **`total_bedrooms`**: Total number of bedrooms in a housing block.
- **`population`**: Population of the locality in a block.
- **`households`**: Total number of families, groups of people residing in a housing unit, per block.
- **`median_income`**: Median income in a block.
- **`ocean_proximity`**: Proximity to the ocean (less than one hour to reach the ocean; inland; near ocean; near bay; on an island).

## Project Steps

1. Importing data and libraries
2. Understanding data and their types
3. Exploratory Data Analysis
4. Feature Engineering
5. Modeling
6. Deployment
