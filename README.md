## Prediction of House Price

# Project motivation
This project aims to investigate what houses for sale are popular and what features can affect the price of houses. The data set is the sale record of KC county, USA,  from Kaggle. 
# Installation
The following three language/libraries are required to run this project.
* Python
* Scikit-Learn
* Matplotlib
# File Descriptions
This project includes two files, the original data set "kc_house_data.csv" and the script "main.ipynb". 

In kc_house_data.csv, the data set includes 19 features such as price, the number of bedroom, the number of bathroom, square feet of house, etc.

In main.ipynb, I first analyze what types of houses are popular based on the count of some features, such as the living area, the number of bedrooms, the number of bathrooms. Then I analyze how long a house needs to be renovated. Finally, I build a basic linear regression model to predict the price of the house and investigate the coefficient between price and different features. 

# results
The prediction model can achieve 67.5% and 67.4% accuracy on training and testing data set. Also, the size of living area,the grade of house and the waterfront are most important features.
