# House Price Prediction

## Project Overview: -

House price prediction is a critical task in real estate analytics, helping stakeholders make informed decisions based on market trends. 
This report compares various machine learning models used to predict house prices using the dataset from the Kaggle competition "House Prices - Advanced Regression Techniques." 

## Data Collection :-

The dataset contains 79 explanatory variables describing aspects of residential homes in Ames, Iowa, aiming to predict the final price of each home.

## Selected Features: 

The selected features for the best model (Random Forest Regression) include:
- MSSubClass
- LotArea
- LotShape
- Neighborhood
- OverallQual
- YearBuilt
- YearRemodAdd
- TotalBsmtSF
- GrLivArea
- GarageCars
- GarageArea
- WoodDeckSF
- BsmtQual
- BsmtFinSF1
- BsmtFinSF
These features were determined to have the most significant impact on predicting house prices based on the model's performance.


## Residual Analysis: 

Residual analysis was conducted to examine the model's performance in predicting house prices.
The residuals were plotted against the predicted values, and the distribution was analyzed to ensure the model's validity.


##	Conclusion: -
In the data analysis process, an exploratory data analysis (EDA) was conducted to examine the dataset. 
During this phase, certain low-impact data points were identified and subsequently removed from consideration. 
In the feature engineering (FE) phase, new data was generated and incorporated into the dataset to enhance its predictive capabilities.
Following the FE stage, a suitable model was selected based on the characteristics of the data. 
Through rigorous experimentation, appropriate parameters were determined for the chosen model, ensuring optimal performance. 
Subsequently, the model was built using the finalized dataset and the identified parameters. 
Perform additional feature engineering (FE) experiments to enhance the quality of the features. 
Explore the implementation of XGBoost and RandomForestRegressor models, considering their suitability for the dataset.
Fine-tune the model parameters to achieve more accurate predictions)
