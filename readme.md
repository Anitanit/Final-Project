Readme
================

The Source file is run\_analysis.R.

Download the dataset if it does not already exist in the working
directory.

Check if zip has already been downloaded in ./projectData directory?
Check if zip has already been unzipped? List all the files of UCI HAR
Dataset folder The files that will be used to load data are listed as
follows: test/subject\_test.txt test/X\_test.txt test/y\_test.txt
train/subject\_train.txt train/X\_train.txt train/y\_train.txt

Load activity, subject and feature info. Read data from the files into
the variables.

Read the Activity files. Read the Subject files. Read Features files.
Merges the training and the test sets to create one data set.

Concatenate the data tables by rows. set names to variables. Merge
columns to get the data frame Data for all data. Extracts only the
measurements on the mean and standard deviation for each measurement.

Subset Name of Features by measurements on the mean and standard
deviation. Subset the data frame Data by selected names of Features.
Uses descriptive activity names to name the activities in the data set.

Read descriptive activity names Factorize variable activity in the data
frame Data using descriptive activity names. Appropriately labels the
data set with descriptive variable names.

Creates a independent tidy dataset that consists of the average (mean)
value of each variable for each subject and activity pair.

Final output file is tidydata.txt
