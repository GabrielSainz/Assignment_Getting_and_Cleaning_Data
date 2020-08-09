# Code Book: Getting and Cleaning Data

## The original data was tranformed by
1. Merging the training and the test sets to create one data set.
2. Extracting only the measurements on the mean and standard deviation for each measurement.
3. Using descriptive activity names to name the activities in the data set
4. Creating a second, independent tidy data set with the average of each variable for each activity and each subject.

File with R code "run_analysis.R" perform 4 following steps. 

## About variables:

| Variable | Description |
| --------------- | --------------- |
| `x_train` | Contain the data from the downloaded files. | 
| `y_train` | Contain the data from the downloaded files. | 
| `x_test` | Contain the data from the downloaded files. | 
| `y_test` | Contain the data from the downloaded files. | 
| `subject_test` | Contain the data from the downloaded files. | 
| `x_data` | Merge the previous datasets to further analysis. | 
| `y_data` | Merge the previous datasets to further analysis. | 
| `subject_data` | Merge the previous datasets to further analysis. | 
| `features` | contains the correct names for the `x_data` dataset, which are applied to the column names stored in | 
