# Getting and Cleaning Data on Coursera: Course Project

=========================================




## The raw data

------------------


The 561 features are unlabeled, as in the x_test.txt file. 
The activity labels are in the y_test.txt file.

The test subjects are in the subject_test.txt file.


The same holds for the training set.



## Run_Analysis script and the tidy dataset

-------------------------------------

The script called run_analysis.R is what I created to obtain the tidy dataset. It will merge the test and training sets together.

Prerequisites for this script:

1. the UCI HAR Dataset must be extracted and
2. the UCI HAR Dataset must be availble in a directory called "UCI HAR Dataset"


The script performs the following functions.
After merging testing and training, labels are added and only columns that have to do with mean and standard deviation are kept.

Lastly, the script will create a tidy data set containing the means of all the columns per test subject and per activity.
This tidy dataset will be written to a tab-delimited file called tidy.txt, which can also be found in this repository.


