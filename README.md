### LHL_Capstone_Project

### PROJECT GOAL

This project focuses on predicting top-selling products on Amazon using data analytics. I've always been intrigued by online selling but struggled to identify the right products. This capstone project is an opportunity to tackle this challenge. Our goal is to provide sellers, including myself, with valuable insights for choosing products . The aim to simplify the decision-making process in the competitive Amazon marketplace, offering a data-driven approach to success. 

### PROCESS OVERVIEW
## STEP 1: DATA ACQUISITION

Identify and select a suitable dataset from Kaggle and then 
Import the CSV file into the project environment
![image](https://github.com/PriyaGanesan2/LHL_Capstone_Project/assets/110922792/d52f3cbb-482a-4dc4-bce2-4247e0c17dbd)

Kaggle Datasource:
https://www.kaggle.com/datasets/asaniczka/amazon-canada-products-2023-2-1m-products




## STEP 2: EDA AND DATA CLEANING

## Utilize Python for EDA and data cleaning.
### 1) Checked the datat set for missing values and negative values and dropped the rows with null product name, null product price and product sold.
### 2) Checked the data for duplicate rows and dropped them from the dataset
### 3) Categorised teh data and grouped them under 15 Unique Categories : Fashion, Home & Kitchen, Beauty & Personal Care, Toys & Games , Automotive", Sports & Outdoors, Hardware & Tools, Health & Wellness & Baby Products, Arts & Crafts, Electronics & Tech", Home & Garden", Travel Essentials", Pet Supplies,Grocery", Party & Sationery & Office Supply
### 4) Created the csv and stored tge clean data in the csv.
 #   Column                Non-Null Count   Dtype  
---  ------                --------------   -----  
 0   asin                  166649 non-null  object 
 1   title                 166649 non-null  object 
 2   imgUrl                166649 non-null  object 
 3   productURL            166649 non-null  object 
 4   stars                 166649 non-null  float64
 5   reviews               166649 non-null  int64  
 6   price                 166649 non-null  float64
 7   listPrice             166649 non-null  float64
 8   categoryName          166649 non-null  object 
 9   isBestSeller          166649 non-null  bool   
 10  boughtInLastMonth     166649 non-null  int64  
 11  mainCategory          146634 non-null  object 
 12  avg_products_per_day  166649 non-null  int64 
### 5) Created best seller csv with best selling details (best seller flag is True)
### 6) Analysed the data using pythin visulatization

### 7) Heatmap : Initial analysis of the heatmap shows no corelation. In the context of predictive modeling, if a heatmap indicates no linear correlation, it suggests that a linear regression model might not be the most suitable approach for predicting the relationship between the variables. I may nee to explore other types of models that can capture non-linear patterns or interactions. 

   ![image](https://github.com/PriyaGanesan2/LHL_Capstone_Project/assets/110922792/2188c6ce-1632-4849-8252-9b12e4f9522c)

        Sports & Outdoors
### 8) EDA to check maximum, minimum and most discounted item under each categoyr
### 9) Price distibution EDA across the main categories showed that most of the best selling products are within the price range of $130 and the most expensive products are under the home & kitchen, Electronics and sports and outdoor.
![image](https://github.com/PriyaGanesan2/LHL_Capstone_Project/assets/110922792/f5657146-11a6-4a60-82f2-e782a7f931a3)

### 10) Rating distribution across categories wrere highly concentrated around 3-5 and probably suggesting that most of the customers rate a product when they are satisfied. 

### 11) Maximum reviewed categories are -  Home & kitchecn, Electronincs & TEch , Fashion, Beauty & Personal Care

![image](https://github.com/PriyaGanesan2/LHL_Capstone_Project/assets/110922792/6780b123-1f70-47ce-91b5-76147bc0e537)

### 12) In summary, 
"Electronics" and "Home & Kitchen" and "Sports & Sports & Outdoor" feature a wide price range, indicating diverse products from low to high-end.
"Home & Kitchen" best-sellers lean towards higher prices.
"Fashion" and "Hardware & Tools" best-sellers are generally more affordable.
Discount Amount
The "Electronics & Tech" category offers the highest average discounts, possibly due to industry competition or higher original prices.
"Fashion" and "Sports & Outdoors" follow with the second and third highest discounts.
"Home & Kitchen" products generally have smaller discounts, suggesting lower markups or fewer promotions.
Product Ratings

Most main categories maintain consistent average ratings, hinting at stable quality across products or well-met customer expectations who like to review a product only when they are satisfied.

## STEP 3: STEP 3: TABLEAU VISUALIZATION
Import the CSV files into Tableau.
Develop workbooks to analyze and visualize key metrics.
Create a comprehensive dashboard that addresses the project goal. 



    




