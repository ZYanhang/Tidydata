# Code Book

## Data Set Information

The data set includes the following files:
  - `X_train.txt` and `X_test.txt`: Contains the feature vectors for the training and test data.
- `y_train.txt` and `y_test.txt`: Contains the activity labels for the training and test data.
- `subject_train.txt` and `subject_test.txt`: Contains the subject IDs for the training and test data.

## Variables

### Features

The data set includes measurements on the mean and standard deviation for each measurement:
  - `TimeBodyAccelerometerMean()-X`
- `TimeBodyAccelerometerMean()-Y`
- ...
- `FrequencyBodyGyroscopeJerkMag-std()`

### Activity Labels

- `Activity`: The activity performed during the measurement (e.g., WALKING, WALKING_UPSTAIRS).

### Subject

- `Subject`: The ID of the subject who performed the activity.

## Transformations

The following transformations were performed to clean up the data:
  1. Merged the training and test sets.
2. Extracted measurements on the mean and standard deviation.
3. Used descriptive activity names.
4. Appropriately labeled the data set with descriptive variable names.
5. Created a second, independent tidy data set with the average of each variable for each activity and each subject.
