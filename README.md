## Getting-and-Cleaning-Data-Project

## Project Overview:
This prject serves to demonstrate the ability to collect, workwith, and clean a dataset known as: Getting and Cleaning Data Course Project. Its goal is to prepare tidy data that can be used for later analysis. A full description of the data used in this course project can be found at

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

And the data for the project can be found at

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

## Required files On this Project include:
1. README.MD - Reading it right now
2. CodeBook.md - decribes the variables, the data, and the transformations that we used in performing the clean up execise
3. run_analysis.R - the actual R code

## Project Summary.
 .Create one R script called run_analysis.R and 
1. merges the training and the test sets to create one data set
2. Extracts only the measurements on the mean and standard deviation for each measurement
3. Uses descriptive activitity names to name the activities in the data set
4. Appropriately labels the dataset with descriptive variable names
5. Create a second, independet tidy set with the avarage of each variable for each activity and each subject.

## Steps:
1. Download the data source into a folder on your local drive. You'll have a UCI HAR Dataset folder.

2. Put run_analysis.R in the parent folder of UCI HAR Dataset, then set it as your working directory using setwd() function in RStudio.

3. Run source("run_analysis.R"), then it will generate a new file tiny_data.txt in your working directory.

## Notes:

run_analysis.R file will help you to install the dependencies automatically. And this will depend on reshape2 and data.table

