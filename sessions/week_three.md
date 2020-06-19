##### Week 3:

Creating new columns from existing columns
 - For loops and list comprehensions
 - Using the df.iterrows() method to iterate through a DataFrame
  

Coding Task:
1. Write a for-loop to iterate through the `income_county_agg` DataFrame and create a list of average incomes for each county. Assign this list to a new column in `income_county_agg` called `avg_income`. 
    - First create an empty list called `avg_inc_list` 
    - Begin the for-loop to iterate through `income_county_agg` 
    - Store the row's total income in a variable called `income`. Remember to multiply total income by 1000 before storing it in order to get the actual amount.
    - Store each row's `return_count` in a variable called `count`.
    - divide `income` by `count`, round it to the nearest whole number, and `append` it to `avg_inc_list`.
    - Assign `avg_income_list` to a new column in `income_county_agg` called `avg_income`.
