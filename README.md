# Cleaning Data for Human Activity Recognition Using Smartphones Dataset

The script run_analysis.R carries out the necessary actions to get a tidy data set the meats the following requirements:
* 1. Merges the training and the test sets to create one data set.
* 2. Extracts only the measurements on the mean and standard deviation for each measurement.
* 3. Uses descriptive activity names to name the activities in the data set
* 4. Appropriately labels the data set with descriptive variable names.
* 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

This is done through the following steps shown in order in the script:
* 1. Loading the necessary libraries
* 2. Reading the train data set
* 3. Reading the test data set
* 4. Merging the X train and test data sets (features data)
* 5. Merging the Y train and test data sets (activities data)
* 6. Reading the features labels
* 7. Renaming the X data set with the features labels
* 8. Renaming the Y data set with "ActivityCode
* 9. Binding Y and X data sets into Z
* 10. Reading the activities labels
* 11. Renaming the activities labels data set
* 12. Joining the activities labels data set with Z data set using the common "ActivityCode"
* 13. Determining the columns representing means and stds
* 14. Subsetting the joint data set by the needed columns (means and stds)
* 15. Calcultating the average of all these features for each activity