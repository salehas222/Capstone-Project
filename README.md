# Capstone-Project
## Project goal:
To determine which cannabis plants are best for medical product.
## Problem statement: 
To determine which cannabis plants are best for medical product.
## EDA Action Plan:
### Determine the size of the data: 
It is important to determine the size of the data when it come to take decision of null value i.e. whether to keep null value or delete it.  So I am going to find the total number of rows using python command dataframe.shape.
### Calculate total number of null values: 
If I know total size of data and total number of null values, It will help me to determine whether to ignore the null value or delete row or columns. For example, if null value is only 5-10% of the data I can delete that row because I won’t loss much information but if it is more than 40 -50% null value I cannot afford to delete that information. In that case I need to think about filling the null value. I will use isnull() and sum () command to find the total number of null value.
### Check the erroneous values: 
Erroneous values are misspelled values, reversed digits or wrong value. It has power to bias the data. As cannabis dataset all independent variable are numeric value, we can use max and min function to find out erroneous values. 
### Change columns name: 
It will be easy if the all column name follows the same standard so I will use rename function to change the all column name. I will prefer all name in lowercase.
### Determine correlation:
If the independent variables are highly correlated our final model will be highly biased. So, in that case, we need to find the correlation between them. I will use heatmap of seaborn library.
### Calculate advanced statistical analysis: 
The statistical analysis helps us to analyzed data pattern. It will give information about maximum, minimum value. I will use describe function for this. It will help me to know if the data is normalized i.e spread equally like a bell shape curve. For this I will use histogram graph. 
Determine the outliers: The outliers can bias the model. Right now, I am not sure whether I will remove the outliers or not, but I will check outliers with the use of Box plot. 
## Model Analysis:
Our goal is to find the best quality cannabis plant. To achieve this, we are going to use Logistic regression model and Support vector machine (SVM) model.
## Results:
### Optimized Linear Regression
![](https://github.com/salehas222/cannabis_model/blob/master/image/Linear.PNG)

### Optimized SVM 
![](https://github.com/salehas222/cannabis_model/blob/master/image/svm.PNG)
