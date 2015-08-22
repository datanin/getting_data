# Course project of the coursera course: Getting and Cleaning Data

The R script `run_analysis.R` is working in the following way.

1. Download the dataset, if it doesn't exists in working directory
2. Load the activity and feature info
3. Loads both the training and test datasets, keeping only those columns which
   reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset and merges those
   columns with the dataset
5. Merges datasets
6. Converts the activity and subject columns into factors
7. Creates a tidy dataset that consists of the average value of each
   variable for each subject and activity pair...

The end result is shown in the file tidy.txt as supposed.

Important: You need the packages reshape2 for this script and run this script from you working dir!