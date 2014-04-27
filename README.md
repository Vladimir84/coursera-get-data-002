coursera-get-data-002
_____________________

Getting and Cleaning Data Course Project

### run_analysis.R

Script does the following: 
* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement. 
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive activity names. 
* Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

This script assumes the Samsung data is extracted in your working directory (so tere's a folder called UCI HAR Dataset/). Only built-in R functions are used as far as I can tell.


### run_analysis_download_data_first.R

Same script as run_analysis.R, but it downloads and extracts data into temporary directory first.
