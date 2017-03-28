Getting and Cleaning Data Course Project
This is an explanation document for the course project of Getting and Cleaning Data Course on Coursera. This document explains how the R script, run_analysis.R,cleans the original dataset and converts it to tidy_data_set.txt (assuming that the original dataset has been downloaded).
 
1. The R script downloads the original dataset and unzips the file. 
2. The R script loads the training and the test sets and merges them to create one data set by merging the measurement variables, the subject id, and the activity id. 
3. The R script extracts only the measurements on the mean and standard deviation for each measurement.
4. The R script labels the data set with descriptive variable names.
5. The R script creates a second, independent tidy data set with the average of each variable for each activity and each subject based on the dataset in above step.

