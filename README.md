## Introduction

  The retails_sales dataset was gotten from Kaggle through the link provided by the instructor of HNG 11 internship program.This data set has 25 attributes also known as column and 2821 records also known as rows. 
 
  This dataset shows the details information of order made by retails transaction across different stores  such as "Order_ID" which is a unique ID given to each transaction made, "ordequantity" that shows the quantity of goods in the order, "priceeach", "order size", details of the customers. 

  This review is aim to identify the key vaeriables and there data types, to determines existing obvious trend, pattern or anormalies in dataset
### Initial Data exploration
Most of the columns in this data are in numerical data type, such as "ordernumber", "QuantityID", "Orderline", "Qtr_id" and "msrp", while we have some that are in text format also known as strings such as "Ordersize","Month" which I created to ease my analysis, "Customerfirstname", "customerlastname" "country", and "region". And we have others in general which is also known as variablecharacters. 
The dataset has lot of empty shell in the "state" and "address line" column which was the reason why I had to delete those columns because it provide no functions to the analysis and can also affect the authentication of the dataset.And also the empty spaces in the "territory" and "postalcode" are replaced with not available by using the function "find and replace" on Excel.
### key variables
Ordernumber: which is the a unique number given to each other made. It's unique because it allows no repetition of a number I.e. Each other has it own order number. 

Status: this shows the transaction status of the order, either being shipped, on hold, cancelled, disputed, in process or resolved.

Productline: it shows the categories of the product being shipped inorder to be able to identify the type of the product. 

Productcode: this is the serial number of the product been ordered.it will serve as primary key to another dataset. 

Dealsize: this shows the size of the order in relating to the sales prices, sales price below 3k were noted as small while the one between 3k and 7k were known as medium and those above 7k were recorded as large   

## Initial insight 
After a quick review of the dataset it can be discovered the dataset has the following:
1. Transactions covered in each Month which allow analysis of sales made in each month over tbe course of the last three years as recorded by the data.

2. It recorded the transactions details of the customer including  their contact address and phone, this suggest that an analysis can be made to discovered the trend in the country
  
3. The dataset include productline which shows the producttype been ordered which allow a data analyst to conduct seasonal, and regional analysis base on product type 
## Observations
1. Monthly Trend: after quick analysis of the dataset, it can be confirmed that November is the month with the most order in both year since the last year record stopped at may and October came next to it. It recorded a total of 10179 unit order in 2003 and 10678 unit order in 2004, while march was the lowest in 2003 and July in 2004 as shown in the illustration below.
2.![yearly analysis](https://github.com/Danboko19/HNG-Stage-0-Report1/assets/148493509/ecd481c3-c8df-4a18-aa57-993181e9f4f1)


3. Regional Analysis: as the dataset shown the territory of each customer that made each transaction, an regional analysis was conducted base on that and it's discovered that "NA" which stand for "North American" made the most order and classic was the most sort after there. Vintage cars came second and motorcycle follows.While plane was the second most sort after in Japan even though it came second to the last in the rest of the region  as shown by the illustration below.
4. ![Classic cars](https://github.com/Danboko19/HNG-Stage-0-Report1/assets/148493509/6d420344-f91c-482a-b35d-1848e50d9fec)


5. Country Analysis: A country analysis was done to determined the five countries with the most order and USA lead the race in this aspect as well as other aspect. Refer to the illustrations below to view the top 5 countries with the most orders.
6. ![Top 5 countries](https://github.com/Danboko19/HNG-Stage-0-Report1/assets/148493509/b4c95df3-e30d-448e-9fdd-9b68f582ac04)

## Conclusions

In conclusion the retail_sale_dataset comprises of detailed information that can be used for well analysis that can drive business decision and improve sales and marketing. Further analysis can be done to determine the most expensive, the most indemand product, as well as the most expensive order and cheapest order. 
## References

Kaggle:https://www.kaggle.com/datasets/kyanyoga/sample-sales-data

HNG_11_internship: https://hng.tech/internship learn from the best in the game and become a wordclass
https://hng.tech/hire start your journey to become a world-class developer
