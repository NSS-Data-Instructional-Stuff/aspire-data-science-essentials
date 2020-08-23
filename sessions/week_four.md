## Week 4:

New Topics:

* Principles for Effective Visualization
* Combining DataFrames: Merging and Concatenating
* `geopandas` and choropleths
  
  
 Coding tasks:
 
  1. Revisit the plots you created last week and make any stylistic improvements that you think are necessary. Check fontsizes, colors, labels, etc.

  2. In the `tn_ha_costs` DataFrame, rename the `analysis_value` column to `ha_avg_cost`. Similarly, in the `tn_cancer_costs` DataFrame, rename the `analysis_value` column to `cancer_avg_cost`.
  
  3. Create a new dataframe, `tn_df` by merging the `county`, `urban`, and `cancer_avg_cost` columns from `tn_cancer_costs` with the `county` and `ha_avg_cost` column from `tn_ha_costs`. Make sure that the resulting DataFrame contains _all_ counties.
  
  4. Create a scatterplot comparing the average cost of a heart attack to the average cost for cancer for each county. What do you notice?
  
  5. Merge the `avg_income` column from `income_county_agg` with `tn_df` and save the result back to `tn_df`. Create two new columns, `ha_cost_income_ratio` and `cancer_cost_income_ratio` by dividing `ha_avg_cost` and `cancer_avg_cost` respectively by `avg_income`.
  
  6. Create two choropleths showing the cost income ratios you calculated in the previous part. What do you notice?
