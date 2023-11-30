# Boston Housing Price Prediction 🏠

## Overview 📜

This project aims to predict the median value of owner-occupied homes in Boston using various statistical features. We leverage the Boston Housing dataset, which contains information collected by the U.S. Census Service, to build and optimize a Random Forest regression model for our predictions.

## Dataset 📊

The dataset consists of 506 entries, each with 14 attributes that capture different aspects of housing and neighborhood characteristics. Notable features include crime rate (`CRIM`), average number of rooms per dwelling (`RM`), pupil-teacher ratio by town (`PTRATIO`), and others.

## Methodology 🔍

We began with exploratory data analysis to understand the data's underlying patterns and relationships. Following this, we preprocessed the data, splitting it into training and testing sets, and then trained a Linear Regression model. To improve prediction accuracy, we transitioned to a more robust Random Forest Regression model and employed GridSearchCV for hyperparameter tuning.

## Results 🏆

The optimized Random Forest model demonstrated promising results:

- Mean Squared Error (MSE): 7.87
- R-squared (R^2) Score: 0.892

These metrics indicate a strong model that can effectively predict housing prices with a high degree of accuracy.

## Conclusion and Discussion 💡

Feature importance analysis revealed that the number of rooms (`RM`) and the percentage of lower status population (`LSTAT`) are the most significant predictors of housing prices. The insights gained from this project can inform real estate stakeholders and contribute to a more nuanced understanding of the housing market in Boston.

## How to Run 🚀

To run this project, ensure you have the following prerequisites installed:

- Python 3.x
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

Clone the repository, navigate to the project directory, and start Jupyter Notebook to run the analysis:

```bash
git clone [repository-link]
cd [project-directory]
jupyter notebook
```

Open the Boston_Housing_Price_Prediction.ipynb notebook and execute the cells sequentially.
