# Customer Review Analysis

Our goal is to perform NLP Techniques on Customer review dataset and compare between machine learning models.


 
 
* 0 represents negative sentiment
* 1 represents positive sentiment


### Dataset
Customer review dataset
* Subject - Subject of the review.
* Customer - Name of the Customer.
* Location -  Location of the customer from where the review is being given.
* Rating - Rating of the product which ranges from 1 to 5
* Data_time - Date and time of the review 
* Views - Number of Views for the review given
* Total_reviews_by_customer - Total number of reviews given by that customer.
* Customer_followers- Number of customers who have followed that customer who have given the review.
* Complaint - Complaint entered by that customer.
* Rows : 130
* Columns : 8 (attributes)

## Data preprocessing performed :
* Converted “Views” column to numerical data.
* Converted “Total_reviews_by_customer” column to numerical data.
* Converted “Customer_follower” column to numerical data.(”NULL” value is converted to 0)
* There are two rows in the column “Views” which are non-numeric - “READ”. So those two rows have been deleted for further analysis. As the number of erroneous data is only 2, so we have deleted the rows,if the number is high we can replace that rows values to either “Mean”,”Median” or “Mode” for filling those rows


## Steps to be performed :
* Used “colab” by Google for reading the dataset.

* Date and time variable in the dataset cannot be used directly for any Inferences.So it is converted to a format that can provide more information like the ones given below.
'Year', 'Month', 'Week', 'Day', 'Dayofweek', 'Dayofyear','Is_month_end', 'Is_month_start', 'Is_quarter_end', 'Is_quarter_start', 'Is_year_end', 'Is_year_start']
## Techniques Used
* Grid Search model selection
* Ensembling (Random Forest)
* linear model (Logistic Regression)

## Requirements
* python --3
* pandas
* sklearn (RandomForest, Grid Search, Logistic Regression)
* numpy
* seaborn

