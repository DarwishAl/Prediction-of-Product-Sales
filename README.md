# Prediction-of-Product-Sales
This project analyzes sales data for the aim of understanding the sales data as it relates to the products and to understand the key business features to build a predictive model that will predict the item sales which will help in buisiness decision-making. 
The analysis highlights trends in sales by outlet type, location, and item features, and predict a model to identify the features that play crucial roles in increasing sales. 

Data
The dataset consists of 8,523 entries with 12 columns, Key columns include:
Item_Identifier: Unique ID for each item
Item_Weight: Item's weight (may contain missing values)
Item_Fat_Content: Fat content category (Low Fat, Regular)
Outlet_Identifier: Unique ID for each outlet
Outlet_Establishment_Year: Year when the outlet was established
Item_Outlet_Sales: Sales value for each item-outlet combination

The The analysis reveals that highest saled product in term of fat content was the low fat products as shown in the histogram below

![Fat_content](https://github.com/user-attachments/assets/f1d2800e-00ba-4454-8d4f-820011ee5b44)

Also, there is no or weak correlation between the differnt fetures of the sales products except for the item outlet sales and item MRP as shown in the heatmap below

   ![feature_correlation](https://github.com/user-attachments/assets/3fdccb48-6311-445b-b822-930975a3c2ef)

Model Summary and Evaluation
Model Selection
To predict the Item_Outlet_Sales, I implemented a linear regression model and the random forest models and trained both models on the dataset.

Model Evaluation
The random forest model achieved an R-squared value of 0.562 on the test set, indicating that only 56% of the variance in sales could be explained by the model. 
The models were overfit and the quality scores in the trainig data showed higher values compared to test data. 








