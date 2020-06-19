##### Week 5:
Building a Classifier
- Overview of Machine Learning
- Feature Engineering
- Scikit Learn's `RandomForestClassifier` 
- One hot encoding to encode categorical variables for use in a model
- Creating training and test data

Coding tasks:
 - What does the exploratory data analysis suggest about our question?
 - Using existing features in the provided datasets or engineering new features from the existing ones, build a `RandomForestClassifier`
    - Use `pd.get_dummies()` with your explanatory variables to encode any categorical values. Features for your model must be numeric.
     - Split the data into train and test sets.
    - Build and evaluate a random forest classifier.
 - Think about other potential features that might explain cost disparities. Can you find additional data that may improve your classifier? The number of healthcare providers in a county, the number of healthcare facilities in a county, unemployment rates, or the per-person-income (which can be approximated using the number of exemptions in the IRS data) are potential features. Can you think of others?
 

    