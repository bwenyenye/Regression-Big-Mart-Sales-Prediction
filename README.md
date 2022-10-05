# Regression-Big-Mart-Sales-Prediction
## H2 About the Project
This a machine learning regression project that predicts the sales data of Big Mart grocery store chain.
## H2 Prerequisities
In this project, the following libraries and dependencies have been used:
* Numpy
* Pandas
* Matplotlib
* Seaborn
* Scikit learn
* LabelEncoder
* XGBRegressor
* metrics
* train_test_split

## H2 Dataset
The Dataset has been obtained from Kaggle and is public [here](/datasets/brijbhushannanda1979/bigmart-sales-data)
The Column labels are as follows:
	* Item_Identifier
  * Item_Weight
  *  Item_Fat_Content
  * Item_Visibility
  * Item_Type
  * Item_MRP
  * Outlet_Identifier
  * Outlet_Establishment_Year
  * Outlet_Size
  * Outlet_Location_Type
  * Outlet_Type
  * Item_Outlet_Sales
  
  The features/ input variables of the dataset are :
  * Item_Identifier
  * Item_Weight
  *  Item_Fat_Content
  * Item_Visibility
  * Item_Type
  * Item_MRP
  * Outlet_Identifier
  * Outlet_Establishment_Year
  * Outlet_Size
  * Outlet_Location_Type
  * Outlet_Type
  
  The target variable/output variable is:
   * Item_Outlet_Sales
  
  
  The Dataset has seven categorical columns which are the following:
  * Item_Identifier 
  * Item_Fat_Content 
  * Item_Type  
  * Outlet_Identifier
  * Outlet_Size
  * Outlet_Location_Type 
  * Outlet_Type 
  
  The dataset has five numeric columns which are the following:
   * Item_Weight
   * Item_Visibility
   * Item_MRP
   * Outlet_Establishment_Year
   * Item_Outlet_Sales 
   
   The following columns of the dataset have missing values:
   * Item_Weight 
   * Outlet_Size 
   
  ## H2 Roadmap
  * The aim of this project is to predict Item_Outlet_Sales based on the features in the dataset.
  * I collected the data from kaggle and found missing values in the columns  Item_Weight  and  Outlet_Size.
  * I replaced the missing values in the Item_Weight  column with the mean and the missing values in the Outlet_Size column with the mode of the column.
  * For the numeric features I used a distribution plot to display the column distributions and used a countplot in the categorical features.
  * The column Item_Fat_Content had three more variations of the same category. I replaced them into two categories of Low Fat and Regular.
  * I took all the categorical values and transformed them to numerical values in the encoding stage.
  * I split the features from the target.
  * The dataset was split into training and testing data in the proportion of 80% to 20% respectively.
  * I modelled the data with an XGBoost Regressor and evaluated the results with the R-squared framework.
  
  
  ## H2 Results and Discussion
  
 
   
  
