##### Week 5:
Building a Classifier
- Overview of Machine Learning
- Feature Engineering
- Scikit Learn's `RandomForestClassifier` 
- One hot encoding to encode categorical variables for use in a model
- Creating training and test data

Coding tasks:
 - What does the exploratory data analysis suggest about our question?
 - Make a copy of your notebook and then remove the `TENNESSEE` filters for the cancer, heart attack, and income data. Be sure to use state and county for any aggregations. You will also need to use the `state_abbrev.csv` file, which lists state names and their 2-character abbreviations, to map the state names in the cancer and heart attack data to their abbreviations **prior** to merging with the income data. The code for mapping will look something like this:
      ```
   state_abbrev=pd.read_csv('../data/state_abbrev.csv')  
   
   ha_costs['state']=ha_costs.state.map(state_abbrev.set_index('name')['abbrev'].to_dict())
   ```

 - Using existing features in the provided datasets or engineering new features from the existing ones, build a `RandomForestClassifier`
    - Use `pd.get_dummies()` with your explanatory variables to encode any categorical values. Features for your model must be numeric.
     - Split the data into train and test sets.
    - Build and evaluate a random forest classifier.
 - Think about other potential features that might explain cost disparities. Can you find additional data that may improve your classifier? The number of healthcare providers in a county, the number of healthcare facilities in a county, unemployment rates, or the per-person-income (which can be approximated using the number of exemptions in the IRS data) are potential features. Can you think of others?
 

    