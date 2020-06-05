how run.analysis.R works
1. downloads from webpage and unzips folder
2. reads datasets containing data, activity labels, column names, subject ids for test and train data into R
3. applies column names for measurements columns in test and train datasets
4. adds a subject id column on the train and test datasets
5. makes column with activity labels on train and test data more descriptive
6. adds column describing activity labels to train and test data
7. merges train and test datasets into a single dataset
8. from dataset in #7, select columns with means and standard deviations
9. creates new dataset including subject id column, activity label column and columns selected in #8
10. create another dataset with mean of each means and standard deviations column for each activity label & subject id
11. put the word "mean" in the names of the columns with the measurements to show that the columns are the means of these measurements
12. rename grouping variables to identify subject id and activity label using rename command in dplyr package
