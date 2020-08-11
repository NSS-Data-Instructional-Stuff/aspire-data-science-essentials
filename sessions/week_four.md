##### Week 4:
Exploratory Data Analysis
- Understanding variable types and assessing missingness
- Use `df.describe()` to begin to get to know your data
- Visualization as a tool for exploration
- Introduction to `matplotlib.pyplot` and `seaborn`
  
  
 Coding tasks:  
  1. Find which datasets have missing values? How many? What should you do about it? 
  2. Create a barplot that shows the average income for each county. Be sure your plot stands alone and is labeled to identify any units.

  3. Create two more barplots: one to show the total cost of a heart attack by county and the other to show the total cost of cancer by county

  4. Create a second DataFrame for `tn_ha_costs` - you can name it `tn_ha_costs2` or something similar - by merging `tn_ha_costs` with `income_county_agg` and keeping just these four columns:`county`, `urban`, `analysis_value`, `avg_income`. Create a `cost_income_ratio` column to compare the total cost (`analysis_value`) to the average annual income. Use the `describe()` function to see the statistical description of the ratio. Repeat this for the cancer dataset.

  5. Create additional plots to investigate the data (for example, you might color the bars by urban vs rural counties; merge the cancer and heart attack cost data and create scatterplots to see if the total cost for cancer is correlated with the total cost for heart attacks, etc.)
  6. Create a choropleth to show `cost_income_ratio levels` for the cancer data.