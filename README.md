# ISM6136.004F22

Using 8 different algorithms to assign risk scores to car insurance applicants based on car features. 

- Kevin Hitt
- Sai Charan Dasari
- Sri Bhargav Lakkireddy
- Nitika Mishra
- Joe Arul Susai Prakash
- Sai Kumar Thatikonda

The focus of this project will be to develop a binary classification model to better predict whether risk is associated with a car based on its attributes. This will aid in the risk assessment process to offer more individualized rates car insurance rates, promoting customer retention and company solvency.

Automobile Data Set (UCI source): This data from the UCI Machine Learning Repository was donated from Carnegie Mellon University and consists of 3 sources (1985 Ward's Automotive Yearbook, Insurance Services Personal Auto Manuals, and IIHS Insurance Collision Report). A paper was written in 1988 by UCI (Source) which used this data in their development of 'instance-based prediction' but did not reference the context of car insurance whatsoever. Similarly a Kaggle competition was held in 2020 with this data where users experimented with a range of predictive models but with a sole focus on model performance rather than deployment.

This establishes a need for our model, as the data has been used to train models but the results from the Kaggle competition are kept private along with the training test split to compare performances. The data has 205 records and 26 features (15 continuous, 1 integer, and 10 nominal), including the integer outcome ranging from -3 to +3.

7 columns have missing values present (normalized-losses, num-of-doors, bore, stroke, horsepower, peak-rpm, and price). 'normalize-losses' has 44 missing values and the remaining columns each have 2 missing values. 44 records represents more than 1/5 of our data so these records will be replaced with the median rather than omitted from analysis.
