# Assigment-Getting-and-Cleaning-Data-Course-Project
Coursera Data Scientist Course - Getting and Cleaning Data Assignment Project

The script run_analysis.r does the following
i)  Loading test data
ii) Loading train data
iii) Loading lookup information (activity and features data)
iv) Merging of test and train data and renaming the merged columns, keeping only those columns which reflect a mean or standard deviation.
v) Merge data frames of different columns to form one data table, write it to a text file namely - "tidy_data.txt"
vi) create a dataset grouped by subject and activity after applying standard deviation and average calculations, writing it to a text file namely - "averaged_tidy_data.txt"

Assumptions: 
- Download the dataset from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and save it in your local working directory
- Install package (data.table) in R
