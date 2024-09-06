# AtliQ-Motors-Electric-Vehicles-Analysis

This project aims to help AtliQ Motors with their research about the electric vehicles market in India, to give them clear understanding of the industry condition, the customers, and the competitors.

# Resources
it's the 12th challenge in the codebasics.io resume projects series, check it here 

# Problem Statement
“AtliQ Motors is an automotive giant in the USA that specializes in electric vehicles (EVs). In the last 5 years, their market share rose to 25% in North America’s electric and hybrid vehicles segment. As a part of their expansion plans, they wanted to launch their bestselling models in India where their market share is less than 2%. Bruce Haryali, the chief of AtliQ Motors India, wanted to do a detailed market study of India’s existing EV/Hybrid market before proceeding further.”

# Data
We have three files

1. electric_vehicle_sales_by_state.csv
- Date: The date on which the data was recorded. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- State: The name of the state where the sales data is recorded. This indicates the geographical location within India.
- Vehicle_Category: The category of the vehicle, specifying whether it is a 2-Wheeler or a 4-Wheeler.
- Electric_Vehicles_sold: The number of electric vehicles sold in the specified state and category on the given date.
- Total_Vehicles_Sold: The total number of vehicles (including both electric and non-electric) sold in the specified state and category on the given date.

2. electric_vehicle_sales_by_makers.csv
- Date: The date on which the sales data was recorded. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- Vehicle_Category: The category of the vehicle, specifying whether it is a 2-Wheeler or a 4-Wheeler.
- Maker: The name of the manufacturer or brand of the electric vehicle.
- Electric_Vehicles_Sold: The number of electric vehicles sold by the specified maker in the given category on the given date.

3. dim_date.csv
- Date: The specific date for which the data is relevant. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- Fiscal_Year: The fiscal year to which the date belongs. This is useful for financial and business analysis.
- Quarter: The fiscal quarter to which the date belongs. Fiscal quarters are typically divided as Q1, Q2, Q3, and Q4.



# Step 1: Searching The domain
1. Articles
   
https://about.crunchbase.com/guide/what-is-market-research/

https://sproutsocial.com/insights/market-research/

https://www.investopedia.com/terms/m/market-research.asp

2. YouTube

https://youtu.be/b-hDg7699S0?feature=shared

https://youtu.be/n27NLTeqxUQ?feature=shared

# Step 2: Exploring The Data 
### Note 
"At the begining I intended to do all the project with python, but i found it more effective to go with Power BI so, i switched to it,
so, these files might seem unorganized, however i'll keep them, consider them drafts"

1. States Dataset [here](https://github.com/taha1048/AtliQ-Motors-Electric-Vehicles-Analysis/blob/main/States.ipynb)
2. Makers Dataset [here](https://github.com/taha1048/AtliQ-Motors-Electric-Vehicles-Analysis/blob/main/Makers.ipynb)

# Step 3: Data Preprocessing
The data was clean I had nothing to do with it except for creating the Fiscal Calendar and here is the data model :

![data model](https://github.com/user-attachments/assets/bafe16ca-b47a-47aa-bfe5-f5e47feeba0e)

# Step 4: Asking Questions (Draft)
These questions are triggers to help me open my eye and delve deeper in the data

- What is the Market's current state? What does the trend look like?
- Where are the opportunities?
- When should we release our models?
- who are the competitors?
- who is leading the market?
- who did well over the years and who didn't?
- who is growing faster than the others?
- customer preferences? 

# Step 5: Analyzing The data with Power BI
I build 3 reports
1. States

