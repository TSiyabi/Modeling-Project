# Modeling-Project

## Objectives
This project simulates a real-world data science task. You will collect property data from two real estate APIs, clean and integrate the data, and then build a robust predictive model based on pricing. The final deliverable is a GitHub repository containing all project artifacts. The primary challenges are to implement the data cleaning process and the predictive model as separate APIs.

## APIs Used for Data Collection
- **API 1 Endpoint:** [https://www.attomdata.com/solutions/property-data-api/](https://www.attomdata.com/solutions/property-data-api/)
- **API 2:** Local API (details in code)

## Steps Taken in Data Collection and Cleaning
1. Ran the API and extracted property data in JSON format.
2. Merged data from both APIs.
3. Cleaned the data by dropping nulls and duplicates.
4. Changed data types as needed.
5. Filled in missing columns.
6. Deleted and dropped unwanted data.

## How to Run and Interact with the Cleaning API
- Start the local cleaning API using the provided script.
- Send your raw property data (JSON) to the API endpoint.
- Receive cleaned and processed data in response.

## Modeling Approach and Results
- Used Decision Tree, Random Forest, and XGBoost algorithms for predictive modeling.
- XGBoost gave the best results (see results section in code/notebook for metrics).

## How to Run and Interact with the Predictive Modeling API
- Start the predictive modeling API using the provided script.
- Send cleaned property data to the API endpoint.
- Receive price predictions
