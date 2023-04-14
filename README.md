## Predictions of Product Sales

The goal of this is to help the retailer understand the properties of products and outlets that play crucial roles in increasing sales. I will use Pandas to load in the data and start exploring and cleaning it.

## Rosa Rocha

## Data Dictionary

<p align = "center"> 
  <img src = "https://github.com/RosaR02/Sales-Predictions/blob/main/screenshots/data%20dictionary.png">
</p>


## DATA CLEANING - To prepare this data, the data was cleaned, and the following processes were performed:
  - Duplicate rows were dropped
  - Rows and Columns (8523, 12)
  - Identify missing values
  - Find and fix any inconsistent categories of data

### Exploratory Data Analysis
    - During the exploratory data analysis, a seaborn countplot and histogram was visualized for numeric datatype column. 
    - Also, a barplot was visualized for categorical column. 
    - This gave a good baseline for the numeric and categorical columns.
    

<p align = "center"> 
  <img src = "https://github.com/RosaR02/Sales-Predictions/blob/main/screenshots/countplot.png">
</p>

This histogram below shows the Medium Outlet Size has more sales than the other 2 Outlet Sizes.

<p align = "center">
   <img src = "https://github.com/RosaR02/Sales-Predictions/blob/main/screenshots/Histplot.png">  
</p>

 ### Explanatory Data Analysis
    - To visualize the data for explantory purposes, two bargraphs were chosen and one linegraph was chosen.
    - The bargraphs were chosen to show how the categories compare to each other. 
    - Finally, a linegraph was chosen to show the outlet type. 


## Explanatory Visuals

<p align = "center">
    <img src = "https://github.com/RosaR02/Sales-Predictions/blob/main/screenshots/barplot.png">
 </p>
 
 This barplot shows the top 5 highest selling items though slighly close by average:
  - Starchy Foods            2374.332773
  - Seafood                  2326.065928
  - Fruits and Vegetables    2289.009592
  - Snack Foods              2277.321739
  - Household                2258.784300
 
 <p align = "center">
    <img src = "https://github.com/RosaR02/Sales-Predictions/blob/main/screenshots/lineplot.png">
 </p>


This lineplot shows that Supermarket type 3 has the most sales compared to the Grocery store which has the lowest of all.


 ### Maching Learning Using the Following Models:
    - Linear Regression Model
    - Decision Tree Regressor Model

    
    
## Models Evaluated & Results

- Linear Regression Model (Testing Set):
  - MAE: 805.5906 
  - MSE: 1,198,635.9796 
  - RMSE: 1,094.8224 
  - R2: 0.5656

- Decision Tree Regressor Model (Testing Set):
  - MAE: 1,036.6259 
  - MSE: 2,205,788.3951 
  - RMSE: 1,485.1897 
  - R2: 0.2005




- The Final Model Chosen was a Linear Regression Model.



## Recommendations

Model Performance
- Overall, the best model is definitely the Linear Regression Model. The difference between the test score and training score was insignificant and by far it outperformed the Decision Tree Regressor model. 


## Limitations & Next Steps

In order to get a more accurate prediction more detailed data will be needed for a better outcome.

## For Further Information

For any additional questions, please contact: 
- Rosa Rocha
- rosarocha0563@gmail.com
