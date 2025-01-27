# Algerian Forest Fires Prediction

## Overview
This project aims to analyze and predict forest fires in Algeria using a dataset that includes various meteorological and environmental factors. The dataset contains instances from two regions of Algeria: Bejaia and Sidi Bel-abbes, covering the period from June 2012 to September 2012.

## Dataset
The dataset includes:
- **Total Instances**: 244
- **Regions**: Bejaia (122 instances) and Sidi Bel-abbes (122 instances)
- **Classes**: Fire (138 instances) and Not Fire (106 instances)

### Attributes
1. **Date**: (DD/MM/YYYY)
2. **Temp**: Temperature (°C)
3. **RH**: Relative Humidity (%)
4. **Ws**: Wind Speed (km/h)
5. **Rain**: Total Rainfall (mm)
6. **FFMC**: Fine Fuel Moisture Code
7. **DMC**: Duff Moisture Code
8. **DC**: Drought Code
9. **ISI**: Initial Spread Index
10. **BUI**: Buildup Index
11. **FWI**: Fire Weather Index
12. **Classes**: Fire or Not Fire

## Data Cleaning and EDA
- The data was cleaned to remove null values and unnecessary columns.
- Exploratory Data Analysis (EDA) was performed to visualize the data and understand the patterns.

## Modeling
The project employs various regression techniques to predict the Fire Weather Index (FWI):
- **Linear Regression**
- **Lasso Regression**
- **Ridge Regression**
- **ElasticNet Regression**

### Model Evaluation
The models were evaluated using Mean Absolute Error (MAE) and R² Score. Cross-validation was also employed to ensure the robustness of the models. This technique involves partitioning the dataset into subsets, training the model on some subsets while validating it on others, which helps in assessing how the results of a statistical analysis will generalize to an independent dataset.

## Requirements
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Usage
To run the analysis, execute the Jupyter notebooks `EDA.ipynb` and `Model.ipynb`.

## Conclusion
The analysis provides insights into the factors contributing to forest fires in Algeria and offers predictive capabilities for future occurrences.
