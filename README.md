# CleaningData
This is a repository for any and all code written for the Getting and Cleaning Data Coursera course through Johns Hopkins University.
Before running the run_analysis code, follow the steps below:
- Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, say C:/Users/yourname/Documents/R/
- Put run_analysis.R into C:/Users/yourname/Documents/R/UCI HAR Dataset
- In RStudio: setwd("C:/Users/yourname/Documents/R/UCI HAR Dataset")and type source("run_analysis.R")
- By typing dat<- read.table("data_set__averages.txt") and dim(dat) +str(dat), we obtain that the table is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. 
