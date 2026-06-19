# Airline Passenger Satistisfaction Analysis

## Project Overview

This data analysis project aim to provide insights into the various services existing within the airline company and how satisfied the customers are and most of all the major services that needs to be improved to enhance customer retention.

### Data sources 

Kaggle: "/kaggle/input/airline-passenger-satisfaction/train.csv"

### Tools

 - Microsoft Excel  (Data Cleaning and Data manipulation)
 - Power BI (Data visualization)

### Data cleaning/preparation

- Checked for duplicates and filtered the columns to check for misspellings to correct them using Find and Replace
- Realized there was a need to group the age column or else I might have visualization problems because there were too many age range in the age column, created another column named 
  “Age Bracket” and grouped it using the IFS function
  (=IF(D2<=12), “Child”, IF(D2<=19), “Teenager”, IF(D2<=29), “Young Adult”, IF(D2<=44), “Middle Aged”, IF(D2<=59), “Older Adult”, IF(D2>59), “Senior”))))))
- Loaded the dataset, cleaned the data and transformed it in Power Query to ensure data was cleaned well.
-	In Power Query checked to see if every column was in a standardized format
-	There were null values in the “Arrival Delay in Minutes” column, so I replaced them with 0 using the “Replace values” option in the Transform tab
-	Data was then loaded for visualization using the “Close & Apply option in Power Query


## Exploratory Data Analysis
### Problem statement

The airline company has some ratio of disloyal customer that remains a challenge due to different expectations of travelers which the company intends to drive to the positive side. The company brought into account rating based on key satisfaction preferences. 
Key challenges include:
-	Analyzing the ratio of satisfied customers to unsatisfied/neutral customers
-	Identifying demographic factors such as gender and age
-	Assessing the count of customers across each class
-	Understanding a few reasons behind customer disloyalty

### Objective

After conducting an analysis through reviews to identify and address the reasons behind customer dissatisfaction, the objective is to determine the factors that most significantly impact passenger satisfaction ( WiFi, baggage handling, seat comfort, inflight entertainment,  on time performance). Identify how to improve operational efficiency such as delays in arrival and departure where the airline is failing to satisfy the passenger’s expectations. 


### Results/ Findings

In conclusion the major setbacks derived from the ratings which includes Poor inflight WiFi service and difficulty in online ticket booking among many others which are inflight entertainment, comfortable seating and overall experience. Consistent efforts to address passenger reviews, implement factors to improve operation efficiency will be a great way to increase passenger’s satisfaction and loyalty.  Ensuring satisfaction involves an approach that combines optimistic transparency with high quality service will help to meet and exceed passenger’s expectations.


### Recommendations

-	Enhance retention and loyalty rewards for Eco class by developing strategies to increase the stability of passengers by handing out 3-time loyalty cards to passengers in which they tick each time they use the airline for accuracy in which after the 3rd usage they get an upgrade to Business class or accessibility to lounge
-	Easy online booking for flights: provide simplicity and directions to navigate through the booking process. Create a better website that can allow multiple booking placements at a time to avoid passengers having a hard time booking tickets and offer transparent pricing with no hidden charges.
-	Proficient WiFi services: adequate provision of strong Wifi  services to passengers as many were dissatisfied with the WIFI services. Ensure the WiFi service is free from technical issues 
-	Comfortable seating and legroom service: Offer convenient seats with adequate legroom service for passengers.
-	Improve operational efficiency by looking into check in issues, arrival delay and departure delay for better passenger convenience.
