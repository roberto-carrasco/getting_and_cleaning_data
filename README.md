# getting_and_cleaning_data

Course project for the "Getting and Cleaning Data" course.
The script, `run_analysis.R`, does the following actions:

1. Download the dataset (if it does not already exist in the working directory)
2. Loads the activity and feature information
3. Loads the training and test datasets, dropping  those columns which
   do not reflect a mean or standard deviation
4. Loads the activity and subject data for each dataset, and merges those
   columns with the dataset
5. Merges the two datasets
6. Converts the `activity` and `subject` columns into factors
7. Creates a tidy dataset that consists of the average (mean) value of each
   variable for each subject and activity pair.

The end result is shown in the file `tidy.txt`.

