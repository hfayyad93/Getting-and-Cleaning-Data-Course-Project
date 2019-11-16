Below are the variables in the final data set:
* 1. Group.1 is the list of activities (LAYING, SITTING, STANDING, WALKING, WALKING_DOWNSTAIRS, WALKING_UPSTAIRS)
* 2. tBodyAcc-XYZ
* 3. tGravityAcc-XYZ
* 4. tBodyAccJerk-XYZ
* 5. tBodyGyro-XYZ
* 6. tBodyGyroJerk-XYZ
* 7. tBodyAccMag
* 8. tGravityAccMag
* 9. tBodyAccJerkMag
* 10. tBodyGyroMag
* 11. tBodyGyroJerkMag
* 12. fBodyAcc-XYZ
* 13. fBodyAccJerk-XYZ
* 14. fBodyGyro-XYZ
* 15. fBodyAccMag
* 16. fBodyAccJerkMag
* 17. fBodyGyroMag
* 18. fBodyGyroJerkMag

Each of the elements 2 to 18 are displayed through their Mean Value mean() and Standard Deviation std() values.

These features shown in this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Also a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

Finally '-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.
