## Introduction
The retails_sales dataset was gotten from Kaggle through the link provided by the instructor of HNG 11 internship program 
This dataset shows the details information of order made by in retails transaction across different stores such as "Order_ID" which is a unique ID given to each transaction made, "ordequantity" that shows the number of goods or items in the order, "priceeach", "order size", details of the customers as well as means of delivery. 
### Initial Data exploration
Most of the columns in this data are in numerical data type, such as "ordernumber", "QuantityID", "Orderline", "Qtr_id" and "msrp", while we have some that are in text format also known as strings such as "Ordersize","Month" which I created to ease my analysis, "Customerfirstname", "customerlastname" "country", and "region". And we have others in general which is also known as variablecharacters. 
The dataset has lot of empty shell in the "state" and "address line" column which was the reason why I had to delete those columns because it provide no functions to the analysis and can also affect the authentication of the dataset.And also the empty spaces in the "territory" and "postalcode" are replaced with not available by using the function "find and replace" on Excel.
### key variables
Order
## Initial insight 
After a quick review of the dataset it can be discovered the dataset has the following:
1. Transactions covered in each Month which allow analysis of sales made in each month over tbe course of the last three years as recorded by the data
2. It recorded the transactions details of the customer including  their contact address and phone, this suggest that an analysis can be made to discovered the trend in the country
3. The dataset include productline which shows the producttype been ordered which allow a data analyst to conduct seasonal, and regional analysis base on product type 
## Observations
Monthly Trend: after quick analysis of the dataset, it can be confirmed that November is the month with the most order in both year since the last year record stopped at may.and October came next to it. It recorded a total of  in 2003 and in 2004, while march was the lowest in 2003 and July in 2004 as shown in the illustration below
Regional Analysis:
