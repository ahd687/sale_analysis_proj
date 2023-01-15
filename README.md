## Sales product  Exploratory Data Analysis

### Code and Resources Used

* Python Version: 3.9.0
* Packages: pandas, numpy, sklearn, matplotlib, seaborn.
* For Web Framework Requirements: pip install -r requirements.txt
* Data : [Kaggle](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data)
* Inspiration: [Kaith Galli Youtub Channel](https://www.youtube.com/@KeithGalli)

### Data Cleaning

After downloading and reading and concatinating all files of my  data in notebook, I needed to clean it up so that it was usable for our model. I made the following changes and created the following variables:
*  Drop rows  with missing values  in columns
*  Drop of rows  with strings such as  'Quantity Ordered' , 'Price Each'
*  Convering the data to correct type 
    * 'Quantity Ordered' to integr 
    * 'Price Each' to float
    * ' Order Data' to Datetime
* Breaked out Address into Individual Columns
    * Address
    * City(State)
    * Zip Code

### Exploratory Data Analysis
We are doing our EDA by responding to the following questions 

1. What was the best month for sales? How much was earned that month?
2. What is the city with hihgest sales?
3. What products are most often sold together ?
4. What products are most often sold together ?
5. What products sold the most?
6. Is the price effect the quantities sold?
 
 The answers are below :
 
![alt text](https://github.com/ahd687/sale_analysis_proj/blob/master/best_moth_sales.png " Best month for sales")
![alt text](https://github.com/ahd687/sale_analysis_proj/blob/master/Hihgest_sales_cities.png " Sales by Cities")
![alt text](https://github.com/ahd687/sale_analysis_proj/blob/master/most_sold_products.png "Most sold products")

