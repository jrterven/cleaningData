## Getting and Cleaning data course project repository

### This repository contains a file called run_analysis.R which generates a tidy data file called tidy_data.txt from the Human Activity Recognition Using Smartphones Data Set. You can obtain this dataset from:

###http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

### Or you can directly download the datase from:
###https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

###run_analysis.R performs the following:

* Merges the training and the test sets to create one data set
* Extracts only the measurements on the mean and standard deviation for each measurement
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive variable names
* Creates a second, independent tidy data set with the average of each variable for each activity and each subject
* Creates a file calle tidy_data.txt