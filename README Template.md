# Prediction of Product Sales
## Using Machine Learning to Forecast Food Item Sales Across Different Outlets 

**Author**: Ansam Aslan

### Business problem:

This project focuses on predicting the sales of food items in different stores. The goal is to help the retailer understand which product and store features affect sales the most. First, the data was cleaned by fixing missing values and errors. Then, visual tools like countplot and heatmaps were used to explore the data and find useful patterns. After understanding the data, a machine learning model was created to predict future sales. This model can help the business make better decisions about prices, stock, and store management to improve total sales.
Ultimately, the insights from this project aim to support strategic inventory planning and optimize revenue.


### Data:
The dataset used in this project contains information about various food items sold at different outlets.
It includes around 8,500 observations and 12 features, such as item type, weight, visibility, MRP (price), and outlet characteristics like size, location, and establishment year.


## Methods
- Data cleaning: handled missing values in “Item_Weight” and “Outlet_Size”.
- Encoding: categorical features were transformed using OneHotEncoder.
- Scaling: numerical features were standardized with StandardScaler.
- Modeling: used multiple regression algorithms, then selected the best-performing one based on MAE,MSE, RMSE and R² score.

## Results

#### frequency of item types by fat content<img 

<img width="912" height="958" alt="image" src="https://github.com/user-attachments/assets/9d3e54c0-565c-45fe-b67d-4bb866d24d6c" />


> This chart shows the frequency of item types by fat content, We observe that 'Low Fat' items have higher sales compared to 'Regular' items, and some item types do not include any regular products.

#### Sales distribution by outlet type<img <img width="578" height="74" alt="image" src="https://github.com/user-attachments/assets/1bd67868-2d55-4510-8a6b-32b9e08e442e" />
This chart shows the sales distribution by outlet type, we notice that Supermarket Type 3 has the highest and most diverse sales, Supermarket Types 1 and 2 have moderate sales, while the Grocery Store has the lowest sales distribution.

## Model

The final model selected was a Random Forest Regressor due to its superior performance and ability to handle both numerical and categorical data effectively.

 Model Performance:
- MAE= 752.432
- MSE= 1,137,654.584
- RMSE= 1,066.609
- R^2= 0.588
   
These results indicate that the model generalizes well and can predict sales with high accuracy.

## Recommendations:

- we recommend that the stakeholder continue selling both types (Low Fat and Regular), with a stronger focus on Low Fat items, as they achieve better results.
- Supermarkets Type1&2 Try to improve them with offers, better product display, and marketing.
- Grocery Stores: improve the products or think about reducing focus on this store type.


## Limitations & Next Steps

More of your own text here


### For further information

For any questions or collaborations, please contact:

📧 ansam.aslan@gmail.com
💼 www.linkedin.com/in/ansam-aslan-b8094a312
🧠 https://github.com/ansam304
