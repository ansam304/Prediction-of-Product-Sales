# Prediction of Product Sales
## “Predicting Food Item Sales Across Multiple Outlets Using Machine Learning” 

**Author**: Ansam Aslan

### Business problem:

This project focuses on predicting the sales of food items in different stores. The goal is to help the retailer understand which product and store features affect sales the most. First, the data was cleaned by fixing missing values and errors. Then, visual tools like countplot and heatmaps were used to explore the data and find useful patterns. After understanding the data, a machine learning model was created to predict future sales, This model provides actionable insights to support better pricing, stock optimization, and strategic store management decisions to maximize overall revenue.


### Data:
The dataset used in this project contains information about various food items sold at different outlets.
It includes around 8,500 observations and 12 features, such as item type, weight, visibility, MRP (price), and outlet characteristics like size, location, and establishment year.


## Methods
- Data cleaning: handled missing values in “Item_Weight” and “Outlet_Size”.
- Encoding: categorical features were transformed using OneHotEncoder.
- Scaling: numerical features were standardized with StandardScaler.
- Modeling: used multiple regression algorithms, then selected the best-performing one based on MAE,MSE, RMSE and R² score.

## Results

#### frequency of item types by fat content

<div align="center">
  <img src="https://github.com/user-attachments/assets/9d3e54c0-565c-45fe-b67d-4bb866d24d6c" width="45%" />
</div>

> This chart shows the frequency of item types by fat content, The plot indicates that low-fat items tend to generate higher sales compared to regular items.

#### Sales distribution by outlet type
<div align="center">
  <img src="https://github.com/user-attachments/assets/9e65f765-56d8-48cb-9856-6cd7724e5769" width="45%" />
</div>

> This chart shows the sales distribution by outlet type, Supermarket Type 3 outlets achieve the highest and most diverse sales distribution, whereas grocery stores record the lowest.

## Model

The final model selected was a Random Forest Regressor due to its superior performance and ability to handle both numerical and categorical data effectively.

 Model Performance:
- MAE= 752.432
- MSE= 1,137,654.584
- RMSE= 1,066.609
- R^2= 0.588
   
These results indicate moderate predictive performance, suggesting that the model successfully captures key sales patterns in the data but could benefit from further tuning, additional features, or deeper exploration to improve accuracy and generalization.

## Recommendations:

- We recommend that stakeholders continue selling both types (Low Fat and Regular), with a stronger focus on Low Fat items, as they achieve better results.
- Supermarket Types 1 & 2: improve performance through offers, better product display, and marketing.
- Grocery Stores: improve the products or think about reducing focus on this store type.


## Limitations & Next Steps

- The model does not consider seasonal or promotional effects that could influence sales.
- Adding time-based variables and external data (like holidays or discounts) could improve prediction accuracy.
- Further hyperparameter tuning and feature selection are recommended for better model generalization.

### For further information

For any questions or collaborations, please contact:

📧  ansam.aslan@gmail.com  
💼  [LinkedIn](https://www.linkedin.com/in/ansam-aslan-b8094a312)  
🧠  [GitHub](https://github.com/ansam304)

