# Coursera_Tidy_Data
Coursea tidy data project files
The script carries out the following steps:
to run te script  run_analysis.R at a very high level it does the following: 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The actual flow of the script is:
1. Install and load all the packages.
2. Read in and combine the train and test data before merginng it.
3. Read in the test data, the labels and subject and merge them into one file called test.
4. Read in the train data, the labels and subject and merge them into one file called train.
5. Merges the training and the test sets to create one data set.
6. Check it the count of rows in the merged data set equals the count of rows in train and test.
7. Appropriately labels the data set with descriptive variable names. read in the variable names
8. Check the rows this should match the number of variables.
9. Create an activity subject dataframe and append the names activity and subject to the file.
10. Add the activity and subject to feature name list which is going to be used to make te column list.
11. Appropriately labels the data set with descriptive variable names. Actaully set the names.
12. Uses descriptive activity names to name the activities in the data set. Use ifelse statement to do this
13. Extracts only the measurements on the mean and standard deviation for each measurement. Use grep to do this into a reduced dataset.
14. Create the tidy data set using dplyr.
15. Suffix "The mean of" to the variable (column) names the mean is calculated for.
16. Wite the tidydata.txt file.


