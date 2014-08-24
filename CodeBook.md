CodeBook
This codebook describes the variables found in the tidy dataset generated by running run_analysis.R

Data Collection Description

The original data set was obtained from [http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones]

It is described as a "Human Activity Recognition database built from the recordings of 30 subjects performing activities of daily living while carrying a waist-mounted smartphone with embedded inertial sensors."

The experiments involved 30 subjects. Each subject performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) with a sensor-equipped smartphone attached to their waist. The smartphone's accelerometer and gyroscope we used to capture 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz.

See the above website for further details on sensor signal pre-processing if you are interested.

Original Data Variable Description

This section is taken directly from the "features_info.txt" file included with the original dataset found at the link above. Rather than attempt to describe all the variables one-by-one, I reprint relevant information from that file here for convenience.

"Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag).

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals).

