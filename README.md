Course Project: Getting and Cleaning Data on Coursera
Author: Kamle5h

The purpose of this project is to demonstrate ability to collect, work with, and clean a data set.
The goal is to prepare tidy data that can be used for later analysis. 

Submissions include: 
1) a tidy data set (tidy_dataset.csv in the results folder)  
2) a link to a Github repository with script for performing the analysis, and 
3) a code book that describes the variables, the data, and any transformations or work that was performed 
to clean up the data called. (CodeBook.md)

The R script run_analysis.R does the following. 
1) Merges the training and the test sets to create one data set.
2) Extracts only the measurements on the mean and standard deviation for each measurement. (mean_and_std.csv in the results folder)
3) Uses descriptive activity names to name the activities in the data set
4) Appropriately labels the data set with descriptive variable names. 
5) Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 
