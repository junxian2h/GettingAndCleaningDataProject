# GettingAndCleaningDataProject
Introduction

This repository contains the submission for the course project for the Coursera course "Getting and Cleaning data".
Project Summary

The following is a summary description of the project instructions

Create one R script called run_analysis.R that does the following. 1. Merges the training and the test sets to create one data set. 2. Extracts only the measurements on the mean and standard deviation for each measurement. 3. Uses descriptive activity names to name the activities in the data set 4. Appropriately labels the data set with descriptive activity names. 5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

Running the test script

The UCI HAR Dataset must be extracted and be availble in a directory called "UCI HAR Dataset" in the 'R Working Directory'.

Run the 'run_analysis.R' script in the working directory.

The 'run_analysis.R' script will create a tidy data set containing the means of all the columns per test subject and per activity. This tidy dataset will be written to a tab-delimited file called 'tidyDataSet.txt', which can also be found in this repository.
