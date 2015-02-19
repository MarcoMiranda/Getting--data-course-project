# Introduction

*This script was written by following the step by step instruction in the R-Studio tutorial on this Coursera Project published October 2014 (https://rstudio-pubs-static.s3.amazonaws.com/37290_8e5a126a3a044b95881ae8df530da583.html)
Reference attribution noted

1. Checks for file existance, creates file named "data" and assignes data from dataset from URL 
2. Assigns to files the dataset from file path 
3. Reads the Activity files
4. Reads the Subject files
5. Reads Fearures files
6. Concatenate the data tables by rows
7. Set names to variables
8. Merge columns to get the data frame Data for all data
9. Subset Name of Features by measurements on the mean and standard deviation
10. Subset the data frame Data by seleted names of Features
11. Read descriptive activity names from “activity_labels.txt”
12. Variables "activity", "subject" and "names" of the activities are labelled using descriptive names
13. "Names of Feteatures" are labelled using descriptive variable names.
14. Creates a second tidy dataset and prints it to a txt file



# Variables

General varible fields are grouped in "activity", "subject" and "names"
variables labels in original data are to the left of the equality and new tidy labels are to the right as per steps 11-13 described before 
*t    = time
*Acc  = Accelerometer
*Gyro = Gyroscope
*f    = frequency
*Mag  = Magnitude
*BodyBody = Body

