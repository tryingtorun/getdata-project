# CODEBOOK for Tidy UCI HARD Dataset

Column | Type | Values | Summary
--- | --- | --- | ---
Subject | Numeric  | 1-30 | Test subject that was observed.
Activity | Alphabetic | WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING | Activity test subject performed when observed.
tBodyAcc.mean...X | standard gravity units 'g' | Normalized [-1,1] | Averaged body acceleration X.
tBodyAcc.mean...Y | standard gravity units 'g' | Normalized [-1,1] | Averaged body acceleration Y.
tBodyAcc.mean...Z | standard gravity units 'g' | Normalized [-1,1] | Averaged body acceleration Z.
tBodyAcc.std...X | standard gravity units 'g' | Normalized [-1,1] | Standard deviation body acceleration X.
tBodyAcc.std...Y | standard gravity units 'g' | Normalized [-1,1] | Standard deviation body acceleration Y.
tBodyAcc.std...Z | standard gravity units 'g' | Normalized [-1,1] | Standard deviation body acceleration Z.
tGravityAcc.mean...X | standard gravity units 'g' | Normalized [-1,1] | Averaged gravity acceleration X.
tGravityAcc.mean...Y | standard gravity units 'g' | Normalized [-1,1] | Averaged gravity acceleration Y.
tGravityAcc.mean...Z | standard gravity units 'g' | Normalized [-1,1] | Averaged gravity acceleration Z.
tGravityAcc.std...X | standard gravity units 'g' | Normalized [-1,1] | Standard deviation gravity acceleration X.
tGravityAcc.std...Y | standard gravity units 'g' | Normalized [-1,1] | Standard deviation gravity acceleration Y.
tGravityAcc.std...Z | standard gravity units 'g' | Normalized [-1,1] | Standard deviation gravity acceleration Z.
tBodyAccJerk.mean...X | standard gravity units 'g' | Normalized [-1,1] | Averaged jerk signals derived from body linear acceleration X.
tBodyAccJerk.mean...Y | standard gravity units 'g' | Normalized [-1,1] | Averaged jerk signals derived from body linear acceleration Y.
tBodyAccJerk.mean...Z | standard gravity units 'g' | Normalized [-1,1] | Averaged jerk signals derived from body linear acceleration Z.
tBodyAccJerk.std...X | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of erk signals derived from body linear acceleration X.
tBodyAccJerk.std...Y | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of erk signals derived from body linear acceleration Y.
tBodyGyro.mean...X | radians/second | Normalized [-1,1] | Averaged angular velocity vector measured by the gyroscope X.
tBodyGyro.mean...Y | radians/second | Normalized [-1,1] | Averaged angular velocity vector measured by the gyroscope Y.
tBodyGyro.mean...Z | radians/second | Normalized [-1,1] | Averaged angular velocity vector measured by the gyroscope Z.
tBodyGyro.std...X | radians/second | Normalized [-1,1] | Standar deviation of angular velocity vector measured by the gyroscope X.
tBodyGyro.std...Y | radians/second | Normalized [-1,1] | Standar deviation of angular velocity vector measured by the gyroscope Y.
tBodyGyro.std...Z | radians/second | Normalized [-1,1] | Standar deviation of angular velocity vector measured by the gyroscope Z.
tBodyGyroJerk.mean...X | radians/second | Normalized [-1,1] | Averaged jerk signals derived from angular velocity X.
tBodyGyroJerk.mean...Y | radians/second | Normalized [-1,1] | Averaged jerk signals derived from angular velocity Y.
tBodyGyroJerk.mean...Z | radians/second | Normalized [-1,1] | Averaged jerk signals derived from angular velocity Z.
tBodyGyroJerk.std...X | radians/second | Normalized [-1,1] | Standard deviation of jerk signals derived from angular velocity X.
tBodyGyroJerk.std...Y | radians/second | Normalized [-1,1] | Standard deviation of jerk signals derived from angular velocity Y.
tBodyGyroJerk.std...Z | radians/second | Normalized [-1,1] | Standard deviation of jerk signals derived from angular velocity Z.
tBodyAccMag.mean.. | standard gravity units 'g' | Normalized [-1,1] | Averaged magnitude of tBodyAcc calculated using the Euclidean norm.
tBodyAccMag.std.. | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of magnitude of tBodyAcc calculated using the Euclidean norm.
tGravityAccMag.mean.. | standard gravity units 'g' | Normalized [-1,1] | Averaged magnitude of tGravityAcc calculated using the Euclidean norm.
tGravityAccMag.std.. | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of magnitude of tGravityAcc calculated using the Euclidean norm.
tBodyAccJerkMag.mean.. | standard gravity units 'g' | Normalized [-1,1] | Averaged magnitude of tBodyAccJerk calculated using the Euclidean norm.
tBodyAccJerkMag.std.. | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of magnitude of tBodyAccJerk calculated using the Euclidean norm.
tBodyGyroMag.mean.. | radians/second | Normalized [-1,1] | Averaged magnitude of tBodyGyro calculated using the Euclidean norm.
tBodyGyroMag.std.. | radians/second | Normalized [-1,1] | Standard deviation of magnitude of tBodyGyro calculated using the Euclidean norm.
tBodyGyroJerkMag.mean.. | radians/second | Normalized [-1,1] | Averaged magnitude of tBodyGyroJerk calculated using the Euclidean norm.
tBodyGyroJerkMag.std.. | radians/second | Normalized [-1,1] | Standard deviation of magnitude of tBodyGyroJerk calculated using the Euclidean norm.
fBodyAcc.mean...X | standard gravity units 'g' | Normalized [-1,1] | Averaged fast fourier tranform of tBodyAcc X.
fBodyAcc.mean...Y | standard gravity units 'g' | Normalized [-1,1] | Averaged fast fourier tranform of tBodyAcc Y.
fBodyAcc.mean...Z | standard gravity units 'g' | Normalized [-1,1] | Averaged fast fourier tranform of tBodyAcc Z.
fBodyAcc.std...X | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyAcc X.
fBodyAcc.std...Y | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyAcc Y.
fBodyAcc.std...Z | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyAcc Z.
fBodyAcc.meanFreq...X | standard gravity units 'g' | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyAcc X.
fBodyAcc.meanFreq...Y | standard gravity units 'g' | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyAcc Y.
fBodyAcc.meanFreq...Z | standard gravity units 'g' | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyAcc Z.
fBodyAccJerk.mean...X | standard gravity units 'g' | Normalized [-1,1] | Averaged fast fourier tranform of tBodyAccJerk X.
fBodyAccJerk.mean...Y | standard gravity units 'g' | Normalized [-1,1] | Averaged fast fourier tranform of tBodyAccJerk Y.
fBodyAccJerk.mean...Z | standard gravity units 'g' | Normalized [-1,1] | Averaged fast fourier tranform of tBodyAccJerk Z.
fBodyAccJerk.std...X | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyAccJerk X.
fBodyAccJerk.std...Y | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyAccJerk Y.
fBodyAccJerk.std...Z | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyAccJerk Z.
fBodyAccJerk.meanFreq...X | standard gravity units 'g' | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyAccJerk X.
fBodyAccJerk.meanFreq...Y | standard gravity units 'g' | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyAccJerk Y.
fBodyAccJerk.meanFreq...Z | standard gravity units 'g' | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyAccJerk Z.
fBodyGyro.mean...X | radians/second | Normalized [-1,1] | Averaged fast fourier tranform of tBodyGyro X.
fBodyGyro.mean...Y | radians/second | Normalized [-1,1] | Averaged fast fourier tranform of tBodyGyro Y.
fBodyGyro.mean...Z | radians/second | Normalized [-1,1] | Averaged fast fourier tranform of tBodyGyro Z.
fBodyGyro.std...X | radians/second | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyGyro X.
fBodyGyro.std...Y | radians/second | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyGyro Y.
fBodyGyro.std...Z | radians/second | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyGyro Z.
fBodyGyro.meanFreq...X | radians/second | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyGyro X.
fBodyGyro.meanFreq...Y | radians/second | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyGyro Y.
fBodyGyro.meanFreq...Z | radians/second | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyGyro Z.
fBodyAccMag.mean.. | standard gravity units 'g' | Normalized [-1,1] | Averaged fast fourier tranform of tBodyAccMag.
fBodyAccMag.std.. | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyAccMag.
fBodyAccMag.meanFreq.. | standard gravity units 'g' | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyAccMag.
fBodyBodyAccJerkMag.mean.. | standard gravity units 'g' | Normalized [-1,1] | Averaged fast fourier tranform of tBodyAccJerkMag.
fBodyBodyAccJerkMag.std.. | standard gravity units 'g' | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyAccJerkMag.
fBodyBodyAccJerkMag.meanFreq.. | standard gravity units 'g' | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyAccJerkMag.
fBodyBodyGyroMag.mean.. | radians/second | Normalized [-1,1] | Averaged fast fourier tranform of tBodyGyroMag.
fBodyBodyGyroMag.std.. | radians/second | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyGyroMag.
fBodyBodyGyroMag.meanFreq.. | radians/second | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyGyroMag.
fBodyBodyGyroJerkMag.mean.. | radians/second | Normalized [-1,1] | Averaged fast fourier tranform of tBodyGyroJerkMag.
fBodyBodyGyroJerkMag.std.. | radians/second | Normalized [-1,1] | Standard deviation of fast fourier tranform of tBodyGyroJerkMag.
fBodyBodyGyroJerkMag.meanFreq.. | radians/second | Normalized [-1,1] | Weighted average of fast fourier tranform of tBodyGyroJerkMag.
angle.tBodyAccMean.gravity. | radians | Normalized [-1,1] | Angle between vectors tBodyAccMean and gravity.
angle.tBodyAccJerkMean..gravityMean. | radians | Normalized [-1,1] | Angle between vectors tBodyJerkMean and gravityMean.
angle.tBodyGyroMean.gravityMean. | radians | Normalized [-1,1] | Angle between vectors tBodyGyroMean and gravityMean.
angle.tBodyGyroJerkMean.gravityMean. | radians | Normalized [-1,1] | Angle between vectors tBodyGyroJerkMean and gravityMean.
angle.X.gravityMean. | radians | Normalized [-1,1] | Angle between vectors X and gravityMean.
angle.Y.gravityMean. | radians | Normalized [-1,1] | Angle between vectors Y and gravityMean.
angle.Z.gravityMean. | radians | Normalized [-1,1] | Angle between vectors Z and gravityMean.