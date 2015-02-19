# Getting--data-course-project
Course project for Coursera Getting and Cleaning Data

This repository hosts the R code and documentation files for the Coursera course "Getting and Cleaning Data" Feburary 2015.

The dataset being used is: [Human Activity Recognition Using Smartphones](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

## Files

The code takes the data from the URL and process it to make a working data set, it then makes changes following the assignment requirements as follows:
 
*Merges the training and the test sets to create one data set.
*Extracts only the measurements on the mean and standard deviation for each measurement. 
*Uses descriptive activity names to name the activities in the data set
*Appropriately labels the data set with descriptive variable names. 
*From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

`CodeBook.md` describes the variables, the data, and any transformations or work that was performed to clean up the data.

`run_analysis.R` contains all the code to perform the analyses described in the 5 steps described above. They can be launched in RStudio by just importing the file.

The output of the 5th step is called `tidydata.txt` that fullfils the requirements of described in the 5 steps and during the course.