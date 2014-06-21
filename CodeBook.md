CodeBook
========

Data Set Information:
=====================

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING-UPSTAIRS, WALKING-DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.


Data Fields
===========
Numeric data (other than subject and activity) are normalized in the range from -1 to 1

subject 
-------
The subject wearing the smartphone

Values: integer [1..30]

activity
-------
The recorded activity

One of  ["Walk", "UpStairs", "DownStairs", "Sit", "Stand", "Lay"]

Body XYZ Acceleration (Mean)
----------------------------
* tBodyAccMeanX
* tBodyAccMeanY
* tBodyAccMeanZ

Body XYZ Acceleration (Standard Deviation)
------------------------------------------
* tBodyAccStDevX
* tBodyAccStDevY
* tBodyAccStDevZ

Gravity XYZ Acceleration (Mean)
-------------------------------
* tGravityAccMeanX
* tGravityAccMeanY
* tGravityAccMeanZ

Gravity XYZ Acceleration (Standard Deviation)
---------------------------------------------
* tGravityAccStDevX
* tGravityAccStDevY
* tGravityAccStDevZ

tBodyAccJerkMeanX
tBodyAccJerkMeanY
tBodyAccJerkMeanZ

tBodyAccJerkStDevX
tBodyAccJerkStDevY
tBodyAccJerkStDevZ

tBodyGyroMeanX
tBodyGyroMeanY
tBodyGyroMeanZ

tBodyGyroStDevX
tBodyGyroStDevY
tBodyGyroStDevZ

tBodyGyroJerkMeanX
tBodyGyroJerkMeanY
tBodyGyroJerkMeanZ

tBodyGyroJerkStDevX
tBodyGyroJerkStDevY
tBodyGyroJerkStDevZ

tBodyAccMagMean
tBodyAccMagStDev

tGravityAccMagMean
tGravityAccMagStDev

tBodyAccJerkMagMean
tBodyAccJerkMagStDev

tBodyGyroMagMean
tBodyGyroMagStDev

tBodyGyroJerkMagMean
tBodyGyroJerkMagStDev

fBodyAccMeanX
fBodyAccMeanY
fBodyAccMeanZ

fBodyAccStDevX
fBodyAccStDevY
fBodyAccStDevZ

fBodyAccJerkMeanX
fBodyAccJerkMeanY
fBodyAccJerkMeanZ

fBodyAccJerkStDevX
fBodyAccJerkStDevY
fBodyAccJerkStDevZ

fBodyGyroMeanX
fBodyGyroMeanY
fBodyGyroMeanZ

fBodyGyroStDevX
fBodyGyroStDevY
fBodyGyroStDevZ

fBodyAccMagMean
fBodyAccMagStDev

fBodyBodyAccJerkMagMean
fBodyBodyAccJerkMagStDev

fBodyBodyGyroMagMean
fBodyBodyGyroMagStDev

fBodyBodyGyroJerkMagMean
fBodyBodyGyroJerkMagStDev
