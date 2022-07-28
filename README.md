
# Project 2: Predicting Price using Linear Regression

### Problem Statement 

We are tasked with creating a model to predict prices for homes given a training dataset and a test set without the salesprice. We are entered in a competition in order to find the best model that would predict prices. My goal is to find the best features to use for our model in order to get the best score.  

### Summary

The dataset was First the columns were set to lower case and snake case. All null values were checked Columns that had over 50% of null values were dropped, which totaled about 5 columns. After dummies were added to dataframe the remaining null values were filled using mean of column Some outliers were removed after testing with models. A LinearRegression model was chosen after finding the highest correlated features to that of saleprice. Other models that were used include Lasso, LassoCV, Ridge, and GridSearchCV. None of which performed better than individually picking columns based on strong correlation to the target value.
 

### Data Dictionary

The dataset for training and test has 80 columns, and then I created dummy variables which resulted in 270 features that were derived from the dataset. The Ames housing dataset dictionary can be found at: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt. 



### Conclusions and Recommendations

 I found that the best features to be used for the model were the ones I show in my notebook.
More tweaking of features such as feature engineering and diving deeper into outliers could improve the model. 
More research into the different kinds of models to make better use of them for feature selection would be required to improve our model as well. 


