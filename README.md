# DSA.-Data-Analysis-project.
This is the first data analysis project I worked on while learning data Analysis with DSA incubator hub

## Case 3: Gender Inequality analysis using Power bi

### Project Overview:
This project aims to generate insights on claims of Gender inequality in three regions of a company. By analyzing specific parameters in the data received, we seeek to gather enough insight to addressing the claims as well as identifying key areas of managerial focus to promote fair treatment within the company and its regions 

table of content
### data sources
The data used were XLsx files and csv files supplied by Incubator hub for use in the final course project folder

### Tools used
Power Bi
   - For data transformation
   - Analysis
   - Report creation
### Data preparation and Cleaning
 - In the initial phase of the project, data files was imported individually on the Power bi desktop and the following actions were undertaken
   1. Data loading and inspection
   2. handling of missing variables
      - Rows with black spaces, empty spaces or null values on the salary column which denoted exited staffs were removed according to the case instruction
      - Rows with null values on the department column were also removed according to the case instruction
      - New conditional column labelled "assigned gender" was created for gender to assign gender as "undisclosed" for staffs who did not disclose their gender while retaining appropriate gender information for staffs with dsclosed gender.
   3. Data cleaning and formatting   
- A total of three data files were transformed and sucessfully uploaded
- concatnate newclumn
- merging tables
- new columns with calculations (add these to data cleansing or not)
### Exploratory data analysis (EDA)
EDA involved exploring the data to answer some case questions such as;
- What is the gender distribution in the organization distil into regions and 
departments 
- Insights on ratings based on gender 
- Analysing the company’s salary structure to identify gender pay gap and insights into departments and regions with identified gender pay gap that should be the focus of 
management 
- Insight into whether or not the company met the recent pay regulation stipulating a minimum employee pay of $90,000 
- visual representation of employee pay distribution grouped in bands of $10,000
-  visual representation of employee pay distribution grouped in bands per region
-  Amount to be paid as a bonus to individual employees
-  Total amount to be paid to individual employees (salary inclusive of 
bonus)
- Total amount to be paid out per region and company-wide
### Data analysis
This is where we included som basic lines of code, queries and Dax expressions to answer case questions based on the data. 
### Result
recommrndations
contributions
license









## Case 1: Amazon case study

### Project Overview
### Data source
### Tools used
### Data preparation and cleaning
- In the initial phase of the project, the data file was uploaded on the excel worksheet and data Inspection and cleaning were carried out by
     1. Removal of duplicates using product id as key
     2. Removal of data rows with blank entries
     3. The multilevel column "category" was split using the text to column function
     4. Using the filter function, incorrect data type was fixed
### Exploratory Data Analysis (EDA)
- EDA involved exploring the data by;
   - creating calculated columns
   - formatting data into table
   - creating a pivot table
- These were done to answer the case questions below.
   - What is the average discount percentage by product category?
   - How many products are listed under each category?
   - What is the total number of reviews per category?
   - Which products have the highest average ratings?
   - What is the average actual price vs the discounted price by category?
   - Which products have the highest number of reviews?
   - How many products have a discount of 50% or more?
   - What is the distribution of product ratings (e.g., how many products are rated 3.0, 
4.0, etc.)?
   - What is the total potential revenue (actual_price × rating_count) by category?
   - What is the number of unique products per price range bucket (e.g., <₹200, 
₹200–₹500, >₹500)?
   - How does the rating relate to the level of discount?
   - How many products have fewer than 1,000 reviews?
   - Which categories have products with the highest discounts?
   - Identify the top 5 products in terms of rating and number of reviews combined.is the total potential revenue by category?
### Data Analysis

     
