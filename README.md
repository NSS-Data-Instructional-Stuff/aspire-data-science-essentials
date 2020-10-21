### Comparing Cost Burden Across TN Counties for Myocardial Infarction and Selected Cancers

**TN Med Helper** is a fictional company that assists patients who are cost-burdened as a result of unexpected medical events. TN Med Helper has approached your data science consultancy for help understanding how to measure the relative burden experienced by patients in TN counties in order to allocate money for relief.

The two most deadly [diseases](https://www.cdc.gov/nchs/pressroom/states/tennessee/tennessee.htm) in Tennessee, according to the Centers for Disease Control and Prevention (CDC) are Heart Disease and Cancer. In this project, we will explore the [Medicare Disparities](https://data.cms.gov/mapping-medicare-disparities) data for acute myocardial infarction (heart attacks) and for colorectal, breast, prostate, and lung cancers. The medicare disparities datasets for the two conditions above include a one-year total cost of care by county for patients with these conditions. Total cost is stored in the column called `analysis_value` for each dataset. The disparities data highlights the fact that the cost for different illnesses varies across geographic regions.

We will also be using the Internal Revenue Service (IRS) data for [individual tax returns for 2016](https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-return-form-1040-statistics). This data includes the number of returns filed by 7 different income groups, a break down by filing status for the returns filed, and the total income reported for each income group by filing status. We will be calculating the average income reported by county, but you may decide to incorporate other aspects of this data into your analysis as time allows.  

By looking at the total cost of care for heart attacks and for cancer we begin to understand cost-of-care disparities. In this project we will look at earnings disparities by examining the IRS income data, and then exploring cost-of-care within the added context of reported earnings by county. We will create a ratio of total-cost-of-care over average income for each county for the two conditions we are looking at in this project.

Next we will build a classifier that **classifies whether a county is above or below the average `cost_income_ratio`** for each disease under consideration. We will create a baseline classifier with our initial datasets, then seek and explore additional data to improve the performance of the classifier.  

Finally, teams will create a presentation to inform **TN Med Helper** of ways the organization might determine where to assist those most in need.

Each week's planned session is outlined in the markdown files in the sessions folder.

