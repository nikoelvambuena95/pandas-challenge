# pandas-challenge

The data set used is user-generated purchase data from a Massive Multiplayer Online Role-Playing Game or MMORPG.
The data set is saved as file name 'purchase_data.csv' in the same folder at the Jupyter Notebook for this project.

The data set 'purchase_data.csv' is data of individual items purchased by MMORPG players using real-world money (U.S. dollars) This data set is comprised of 7 different data values divided into 7 respective columns.

The columns of the data set 'purchase_data.csv' are as follows:
- 'Purchase ID' = unique ID of individual item purchase
- 'SN' = user-generated usersname
- 'Age' = player's age (self-reported)
- 'Gender' = player's gender (self-reported)
- 'Item ID' = unique ID of item
- 'Price' = current price of item (unit of U.S. dollars["$"])

The data was provided in .csv (comma-seperated values) format and was both collected and analysed using 'pandas' software library. 

7 types of analyses were conducted on this original data set.

The analyses are as follows:
1. 'Total Players' = total player count
2. 'Puchasing Analysis (Total)' = analysis of total purchases
3. 'Gender Demographics' = Player demogrpahics by Gender
4. 'Purchasing Analysis (Gender)' = analysis of total purchases by gender
5. 'Top Spenders' = top spenders grouped by 'SN' or unique players
6. 'Most Popular Items' = items purchased the most
7. 'Mot Profitable Items' = items purchased the most, sorted in descending order by 'Total Purchase Value'

Duplicate values for 'SN' were removed for analyses regarding individual player attributes - i.e. gender.
Except for total counts, all numerical values are rounded to two decimal places - i.e. '1.2345' to '1.23'.
Numerical values were converted into their appropriate formats - i.e. currency and precentages. 

The variable names for the analyses are as follows:
1. 'Total Players' = total_players_df
2. 'Purchasing Analysis (Total)' = purchasing_analysis_total_df
3. 'Gender Demographics' = gender_dem_df
4. 'Purchasing Analysis (Gender)' = purchase_gender_df
5. 'Age Demographics' = purchase_age_dem_df
6. 'Purchasing Analysis (Age)' = purchase_analysis_age_df
7. 'Top Spenders' = spenders_analysis_df
8. 'Most Popular Items' = popular_items_df
9. 'Most Profitable Items' = profitable_items_df

There are errors in the scripting with creating the data frames for the anlalyses. Instead of merging columns, the method of adding columns to a data frame was used. I had difficulties with sorting the the final analysis - 'Most Profitable Items'. 
