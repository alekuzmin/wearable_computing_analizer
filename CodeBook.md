# Code Book

This code book summarizes the resulting data fields in tidydata.txt.

## Identifiers

subject - The ID of the test subject

activity - The type of activity performed when the corresponding measurements were taken

## Fields Description

The original files have this description

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ.

These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz.

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals).

These signals were used to estimate variables of the feature vector for each pattern:
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.## Measurements

In my dataset, each field has the same meaninig, but it contents the mean grouped by subject and activity.

The variabls selected are

subject

activit

tBodyAccMeanX

tBodyAccMeanY

tBodyAccMeanZ

tGravityAccMeanX

tGravityAccMeanY

tGravityAccMeanZ

tBodyAccJerkMeanX

tBodyAccJerkMeanY

tBodyAccJerkMeanZ

tBodyGyroMeanX

tBodyGyroMeanY

tBodyGyroMeanZ

tBodyGyroJerkMeanX

tBodyGyroJerkMeanY

tBodyGyroJerkMeanZ

tBodyAccMagMean

tGravityAccMagMean

tBodyAccJerkMagMean

tBodyGyroMagMean

tBodyGyroJerkMagMean

fBodyAccMeanX

fBodyAccMeanY

fBodyAccMeanZ

fBodyAccJerkMeanX

fBodyAccJerkMeanY

fBodyAccJerkMeanZ

fBodyGyroMeanX

fBodyGyroMeanY

fBodyGyroMeanZ

fBodyAccMagMean

fBodyBodyAccJerkMagMean

fBodyBodyGyroMagMean

fBodyBodyGyroJerkMagMean

tBodyAccStdX

tBodyAccStdY

tBodyAccStdZ

tGravityAccStdX

tGravityAccStdY

tGravityAccStdZ

tBodyAccJerkStdX

tBodyAccJerkStdY

tBodyAccJerkStdZ

tBodyGyroStdX

tBodyGyroStdY

tBodyGyroStdZ

tBodyGyroJerkStdX

tBodyGyroJerkStdY

tBodyGyroJerkStdZ

tBodyAccMagStd

tGravityAccMagStd

tBodyAccJerkMagStd

tBodyGyroMagStd

tBodyGyroJerkMagStd

fBodyAccStdX

fBodyAccStdY

fBodyAccStdZ

fBodyAccJerkStdX

fBodyAccJerkStdY

fBodyAccJerkStdZ

fBodyGyroStdX

fBodyGyroStdY

fBodyGyroStdZ

fBodyAccMagStd

fBodyBodyAccJerkMagStd

fBodyBodyGyroMagStd

fBodyBodyGyroJerkMagStd

## Activity Labels

WALKING (value 1): subject was walking during the test

WALKING_UPSTAIRS (value 2): subject was walking up a staircase during the test

WALKING_DOWNSTAIRS (value 3): subject was walking down a staircase during the test

SITTING (value 4): subject was sitting during the test

STANDING (value 5): subject was standing during the test

LAYING (value 6): subject was laying down during the test Status API Training Shop Blog About Pricing