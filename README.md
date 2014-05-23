##Running run_analysis.R
========================================================

This script uses the dataset "Human Activity Recognition Using Smartphones Data Set" from the UCI Machine Learning Repository. URL: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

This is a direct link to the raw data files: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The data needs to be downloaded and unzipped to your working directory. When the files are unzipped, it should create a sub-folder called "UCI HAR Dataset". This folder's structure needs to be in place in order for the script to work. The run_analysis.R script file will need to be in your working directory.

The run_analysis.R script will read the testing and training datasets and combine them into one big data set. This combined data set is then summarized in to a tidy data set (tidy_data.txt).

###Short description of the data

The first column of the tidy data set are just row numbers (a total of 180) which consists of a combination of the 30 subjects and the 6 activities each subject conducted, giving a total of 6*30=180 rows. Column 2 contains the activity labels and column 3 contains the subject number. The remainder of the columns contain the summarized data (the average values for the mean and standard deviation features from the original data set).

