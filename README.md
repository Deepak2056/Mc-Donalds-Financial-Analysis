# Indianhousingmarket
## A brief analysis using publicly available dataset about housing market in India

### Information
    - Dataset - https://www.kaggle.com/datasets/rakkesharv/real-estate-data-from-7-indian-cities
    - Dataset format - Microsoft Excel
    - Tools used - Microsoft Excel and Power BI
    - Files Location
    
### Objective
    Understand range of pricing for each housing category
    Understand the correlation between area and price for each city and housing category
    Which one is expensive across different cities - Flat or independent housing
    Does having a balcony make a house expensive?
    
### Data Cleaning
    Extract Property name
    Extract BHK detail from *Property Title*
    Extract Independent House vs Flat
    Convert Price column
    Location - Create an extracted column to show city
    
### Process
    - Data hosted on cloud service and connected to give flexibility for data changes
    - Transformations done in Power Query
        - Converted price formats to INR
        - Added Index column
        - Created measures using DAX
            - MAX per sq ft
            - MIN per sq ft
            - MAX Total Price
            - MIN Total Price
            - AVG Price Per Sqft
            
### Visualizations Created
    Minimum, Average and Maximum Bar Chart for each Flat type across all sizes and cities
    Area vs Price scatter plot for each flat type across all sizes and cities
    Comparison bar chart to understand average price per sq ft in each city for a flat and independent house.
    Bar chart for average price per sq ft for every city distributed by flat vs independent house
    
### Insights
    - Delhi has the largest range between lowest and highest per sqft. for both 1BHK and 2BHK formats
    - Most expensive properties in categories of 1BHK and 2BHK can be seen in Bangalore and New Delhi
    - Pune maintains to be more affordable across all three ranges of maximum, min and average price
    - Pune seems to be on the higher price range if we talk about 3BHK
    - New Delhi seems to be on the higher price range in 4BHK segment
    - Mumbai looks like to have the smallest range of price in 3BHK as well as 4BHK
    - Kolkata seems to be the most affordable in the 4BHK in all the price range
    - Mumbai prices are more concentrated on upwards of 1CR INR while the rest of them have the upper limit at 1CR
    - Mumbai, Kolkata and Pune seem to have the least number of outliers, and the price range are also on similar range
    - Chennai, Bangalore and New Delhi seem to have a greater number of outliers with Chennai getting the least area for expensive price and largest area for least price in Bangalore.
    - Chennai, Bangalore and Mumbai seem to have more range in the prices offered per sqft for 3BHK.
    - Chennai, Bangalore and Delhi offer more in terms of area range as compared to other cities
    - New Delhi, Mumbai and Bangalore offer huge range of price as well as area for the properties listed in 4BHK
    - Chennai, Kolkata and Pune have more concentrated range of price vs area
    - Independent house are more costly in terms of Price per sqft across all cities
    - Out of all cities, average price per sqft is highest in Mumbai. The next in line is New Delhi with a difference of almost 7k per sqft
    - Average Independent House in Kolkata is 26 times expensive than a flat in the same city. This is the highest difference seen from all cities.
    - While in general, independent house is still expensive than flat overall in 2BHK format, its more evident in Kolkata, Mumbai, New Delhi and Pune.
    - Highest difference between flat and house in this as well comes from Kolkata.
    - While average price per sqft has been higher in independent house than flats, this has changed for Mumbai in 3BHK where the Flat is more expensive.
    - In 4BHK as well, we see Mumbai has average price per sq ft higher for flat than independent houses. The difference seems to be almost 2 times the price of independent house.
    - In both types of houses, 4BHK formats seem to be more expensive if they have a balcony.
    - 1 BHK independent house with a balcony is most expensive out of all others.
### Brief Visuals
Some sample visuals from the analysis. Please refer to the pdf file attached for full picture
![image](https://github.com/user-attachments/assets/605cf66e-a0f8-47be-9e86-ce68ce906808)
![image](https://github.com/user-attachments/assets/7faf68a0-216d-4906-a5c2-b99c34db7fdf)
![image](https://github.com/user-attachments/assets/42c97527-3302-4905-87bf-f3dfed9e5c59)



