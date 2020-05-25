CODEBOOK
================

## Codebook

The run\_analysis.R script performs the getting and cleaning data and to
prepare the tidy data to use for later purpose. The data is collected
from the accelerometers from the Samsung Galaxy S smartphone.

The experiments have been carried out with a group of 30 volunteers
within an age bracket of 19-48 years. Each person performed six
activities (WALKING, WALKING\_UPSTAIRS, WALKING\_DOWNSTAIRS, SITTING,
STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the
waist. Using its embedded accelerometer and gyroscope, we captured
3-axial linear acceleration and 3-axial angular velocity at a constant
rate of 50Hz. The experiments have been video-recorded to label the data
manually. The obtained dataset has been randomly partitioned into two
sets, where 70% of the volunteers was selected for generating the
training data and 30% the test data.

The sensor signals (accelerometer and gyroscope) were pre-processed by
applying noise filters and then sampled in fixed-width sliding windows
of 2.56 sec and 50% overlap (128 readings/window). The sensor
acceleration signal, which has gravitational and body motion components,
was separated using a Butterworth low-pass filter into body acceleration
and gravity. The gravitational force is assumed to have only low
frequency components, therefore a filter with 0.3 Hz cutoff frequency
was used. From each window, a vector of features was obtained by
calculating variables from the time and frequency domain.

Dataset downloaded and extracted under the folder called UCI HAR Dataset
subject is the ID of 30 volunteers with age between 1 to 30 Activity is
the type of activity like walking, walking\_upsatirs,
walking\_downstairs, sitting, standing, laying. These signals were used
to estimate variables of the feature vector for each pattern: ‘-XYZ’ is
used to denote 3-axial signals in the X, Y and Z directions.

timeBodyAccelerometer-XYZ timeGravityAccelerometer-XYZ
timeBodyAccelerometerJerk-XYZ timeBodyGyroscope-XYZ
timeBodyGyroscopeJerk-XYZ timeBodyAccelerometerMagnitude
timeGravityAccelerometerMagnitude timeBodyAccelerometerJerkMagnitude
timeBodyGyroscopeMagnitude timeBodyGyroscopeJerkMagnitude
frequencyBodyAccelerometer-XYZ frequencyBodyAccelerometerJerk-XYZ
frequencyBodyGyroscope-XYZ frequencyBodyAccelerometerMagnitude
frequencyBodyAccelerometerJerkMagnitude frequencyBodyGyroscopeMagnitude
frequencyBodyGyroscopeJerkMagnitude

Variable estimated are mean(): Mean value std(): Standard deviation

Tidy Data Structure timeBodyAccelerometer-mean()-X (radians per sec)
timeBodyAccelerometer-mean()-Y (radians per sec)
timeBodyAccelerometer-mean()-Z (radians per sec)
timeBodyAccelerometer-std()-X (radians per sec)
timeBodyAccelerometer-std()-Y (radians per sec)
timeBodyAccelerometer-std()-Z (radians per sec)
timeGravityAccelerometer-mean()-X (radians per sec)
timeGravityAccelerometer-mean()-Y (radians per sec)
timeGravityAccelerometer-mean()-Z (radians per sec)
timeGravityAccelerometer-std()-X (radians per sec)
timeGravityAccelerometer-std()-Y (radians per sec)
timeGravityAccelerometer-std()-Z (radians per sec)
timeBodyAccelerometerJerk-mean()-X (radians per sec)
timeBodyAccelerometerJerk-mean()-Y (radians per sec)
timeBodyAccelerometerJerk-mean()-Z (radians per sec)
timeBodyAccelerometerJerk-std()-X (radians per sec)
timeBodyAccelerometerJerk-std()-Y (radians per sec)
timeBodyAccelerometerJerk-std()-Z (radians per sec)
timeBodyGyroscope-mean()-X (radians per sec) timeBodyGyroscope-mean()-Y
(radians per sec) timeBodyGyroscope-mean()-Z (radians per sec)
timeBodyGyroscope-std()-X (radians per sec) timeBodyGyroscope-std()-Y
(radians per sec) timeBodyGyroscope-std()-Z (radians per sec)
timeBodyGyroscopeJerk-mean()-X (radians per sec)
timeBodyGyroscopeJerk-mean()-Y (radians per sec)
timeBodyGyroscopeJerk-mean()-Z (radians per sec)
timeBodyGyroscopeJerk-std()-X (radians per sec)
timeBodyGyroscopeJerk-std()-Y (radians per sec)
timeBodyGyroscopeJerk-std()-Z (radians per sec)
timeBodyAccelerometerMagnitude-mean() (radians per sec)
timeBodyAccelerometerMagnitude-std() (radians per sec)
timeGravityAccelerometerMagnitude-mean() (radians per sec)
timeGravityAccelerometerMagnitude-std() (radians per sec)
timeBodyAccelerometerJerkMagnitude-mean() (radians per sec)
timeBodyAccelerometerJerkMagnitude-std() (radians per sec)
timeBodyGyroscopeMagnitude-mean() (radians per sec)
timeBodyGyroscopeMagnitude-std() (radians per sec)
timeBodyGyroscopeJerkMagnitude-mean() (radians per sec)
timeBodyGyroscopeJerkMagnitude-std() (radians per sec)
frequencyBodyAccelerometer-mean()-X (hertz)
frequencyBodyAccelerometer-mean()-Y (hertz)
frequencyBodyAccelerometer-mean()-Z (hertz)
frequencyBodyAccelerometer-std()-X (hertz)
frequencyBodyAccelerometer-std()-Y (hertz)
frequencyBodyAccelerometer-std()-Z (hertz)
frequencyBodyAccelerometerJerk-mean()-X (hertz)
frequencyBodyAccelerometerJerk-mean()-Y (hertz)
frequencyBodyAccelerometerJerk-mean()-Z (hertz)
frequencyBodyAccelerometerJerk-std()-X (hertz)
frequencyBodyAccelerometerJerk-std()-Y (hertz)
frequencyBodyAccelerometerJerk-std()-Z (hertz)
frequencyBodyGyroscope-mean()-X (hertz) frequencyBodyGyroscope-mean()-Y
(hertz) frequencyBodyGyroscope-mean()-Z (hertz)
frequencyBodyGyroscope-std()-X (hertz) frequencyBodyGyroscope-std()-Y
(hertz) frequencyBodyGyroscope-std()-Z (hertz)
frequencyBodyAccelerometerMagnitude-mean() (hertz)
frequencyBodyAccelerometerMagnitude-std() (hertz)
frequencyBodyAccelerometerJerkMagnitude-mean() (hertz)
frequencyBodyAccelerometerJerkMagnitude-std() (hertz)
frequencyBodyGyroscopeMagnitude-mean() (hertz)
frequencyBodyGyroscopeMagnitude-std() (hertz)
frequencyBodyGyroscopeJerkMagnitude-mean() (hertz)
frequencyBodyGyroscopeJerkMagnitude-std() (hertz)

Final dataset is in the table format.
