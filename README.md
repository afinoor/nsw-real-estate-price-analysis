# NSW Real Estate Price Prediction Models

## Introduction

In this project, I aim to build and evaluate predictive models to estimate the purchase price of properties in NSW with high accuracy. The dataset for this analysis was collected from Kaggle, which was originally scraped from the official NSW government website that publicly shares property sales data on a weekly basis. This comprehensive dataset allows for an in-depth analysis of property prices based on various attributes recorded in the Register of Land Values and Notices of Sale.

## Project Structure

- **Introduction:** Overview of the project's objectives and the target audience.
- **Data Introduction:** Explanation of the dataset's origin and its comprehensive elements.
- **Data Loading and Cleaning:** Steps for importing, cleaning, and preprocessing the dataset.
- **Exploratory Data Analysis:** Initial exploration to understand data characteristics and identify potential predictors.
- **Model Building:**
  - **Linear Regression Model:** Development and training of a linear regression model.
  - **Decision Tree Regressor:** Development and training of a decision tree model for comparison.
- **Model Evaluation:** Evaluation of model performance using metrics like MSE, RMSE, and R-Squared values.
- **Conclusion:** Summary of model performances and recommendations for model selection based on the analysis results.

## Files Included

- `main.ipynb`: The Jupyter notebook containing the detailed analysis and model evaluations.
- `nsw_australia_property_data.csv`: The dataset used for the analysis, detailing various properties and their sale prices.

## Getting Started

Begin with the `main.ipynb` notebook to follow the detailed analysis process from data exploration to model evaluation. The notebook provides insights into the predictive modeling techniques used and their effectiveness in predicting property prices.

## Dataset

The dataset includes detailed attributes of properties in NSW, Australia, such as:

- **Geographical identifiers:** District Code, Property ID, and Locality.
- **Property specifics:** Property Name, Unit Number, House Number, Street Name, and Post Code.
- **Land and area details:** Area measurement in square metres or hectares, and Area Type.
- **Transactional data:** Contract Date, Settlement Date, and Purchase Price.
- **Zoning and usage information:** Zoning classification, Nature of Property, and Primary Purpose.

These elements are crucial for building accurate models as they provide extensive insights into each property's characteristics and market value conditions.

## Findings

The analysis highlights the importance of feature selection in predictive modeling and demonstrates the effectiveness of logistic regression and KNN in classifying mobile price ranges. The comparison between models based on accuracy revealed that while logistic regression showed higher accuracy on the test set, KNN, with its robust cross-validation, was preferred due to better generalization.

## Conclusion

The linear regression model is recommended for predicting property purchase prices (this dataset only, for other dataset the scenarion might be different based on the dynamics of the data) due to its robustness and higher performance metrics. This model provides a more reliable basis for property valuation compared to decision tree models, which may overfit noisy data.
