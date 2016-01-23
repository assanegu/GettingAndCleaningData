## Getting and Cleaning Data Codebook
# This file contain the description of all the variable


## variable names and description (the values represent the average):

# activity: represent the following activite:
#  1. WALKING
#  2. WALKING_UPSTAIRS
#  3. WALKING_DOWNSTAIRS
#  4. SITTING
#  5. STANDING
#  6. LAYING

# subject: is the subject identification number. 
# For the following variables, we will use the description provided in the original detaset...
#The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals timeAccelerometer-XYZ and timeGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (timeBodyAcc-XYZ and timeGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

#Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

#Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, #frequencyBodyGyro-XYZ, frequencyBodyAccJerkMag, frequencyBodyGyroMag, frequencyBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

#These signals were used to estimate variables of the feature vector for each pattern:  
#'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

#timeBodyAccelerometer-XYZ
timeGravityAccelerometer-XYZ
#timeBodyAccJerk-XYZ
#timeBodyGyro-XYZ
#timeBodyGyroJerk-XYZ
#timeBodyAccMag
timeGravityAccMag
#timeBodyAccJerkMag
#timeBodyGyroMag
#timeBodyGyroJerkMag
#frequencyBodyAcc-XYZ
#frequencyBodyAccJerk-XYZ
#frequencyBodyGyro-XYZ
#frequencyBodyAccMag
#frequencyBodyAccJerkMag
#frequencyBodyGyroMag
#frequencyBodyGyroJerkMag

#The set of variables that were estimated from these signals are: 

#mean(): Mean value
#std(): Standard deviation
#mad(): Median absolute deviation 
#max(): Largest value in array
#min(): Smallest value in array
#sma(): Signal magnitude area
#energy(): Energy measure. Sum of the squares divided by the number of values. 
#iqr(): Interquartile range 
#entropy(): Signal entropy
#arCoeff(): Autorregresion coefficients with Burg order equal to 4
#correlation(): correlation coefficient between two signals
#maxInds(): index of the frequency component with largest magnitude
#meanFreq(): Weighted average of the frequency components to obtain a mean frequency
#skewness(): skewness of the frequency domain signal 
#kurtosis(): kurtosis of the frequency domain signal 
#bandsEnergy(): Energy of a frequency interval within the 64 bins of the FFT of each window.
#angle(): Angle between to vectors.


#timeBodyAccelerometer-mean()-X                 
#timeBodyAccelerometer-mean()-Y                
#timeBodyAccelerometer-mean()-Z                 
#timeBodyAccelerometer-std()-X                 
#timeBodyAccelerometer-std()-Y                  
#timeBodyAccelerometer-std()-Z                 
timeGravityAccelerometer-mean()-X              
timeGravityAccelerometer-mean()-Y             
timeGravityAccelerometer-mean()-Z              
timeGravityAccelerometer-std()-X              
timeGravityAccelerometer-std()-Y               
timeGravityAccelerometer-std()-Z              
#timeBodyAccelerometerJerk-mean()-X             
#timeBodyAccelerometerJerk-mean()-Y            
#timeBodyAccelerometerJerk-mean()-Z             
#timeBodyAccelerometerJerk-std()-X             
#timeBodyAccelerometerJerk-std()-Y              
#timeBodyAccelerometerJerk-std()-Z             
#timeBodyGyroscope-mean()-X                     
#timeBodyGyroscope-mean()-Y                    
#timeBodyGyroscope-mean()-Z                     
#timeBodyGyroscope-std()-X                     
#timeBodyGyroscope-std()-Y                      
#timeBodyGyroscope-std()-Z                     
#timeBodyGyroscopeJerk-mean()-X                 
#timeBodyGyroscopeJerk-mean()-Y                
#timeBodyGyroscopeJerk-mean()-Z                 
#timeBodyGyroscopeJerk-std()-X                 
#timeBodyGyroscopeJerk-std()-Y                  
#timeBodyGyroscopeJerk-std()-Z                 
#timeBodyAccelerometerMagnitude-mean()          
#timeBodyAccelerometerMagnitude-std()          
#timeGravityAccelerometerMagnitude-mean()       
timeGravityAccelerometerMagnitude-std()       
#timeBodyAccelerometerJerkMagnitude-mean()      
#timeBodyAccelerometerJerkMagnitude-std()      
#timeBodyGyroscopeMagnitude-mean()              
#timeBodyGyroscopeMagnitude-std()              
#timeBodyGyroscopeJerkMagnitude-mean()          
#timeBodyGyroscopeJerkMagnitude-std()          
#frequencyBodyAccelerometer-mean()-X            
#frequencyBodyAccelerometer-mean()-Y           
#frequencyBodyAccelerometer-mean()-Z            
#frequencyBodyAccelerometer-std()-X            
#frequencyBodyAccelerometer-std()-Y             
#frequencyBodyAccelerometer-std()-Z            
#frequencyBodyAccelerometerJerk-mean()-X        
#frequencyBodyAccelerometerJerk-mean()-Y       
#frequencyBodyAccelerometerJerk-mean()-Z        
#frequencyBodyAccelerometerJerk-std()-X        
#frequencyBodyAccelerometerJerk-std()-Y         
#frequencyBodyAccelerometerJerk-std()-Z        
#frequencyBodyGyroscope-mean()-X                
#frequencyBodyGyroscope-mean()-Y               
#frequencyBodyGyroscope-mean()-Z                
#frequencyBodyGyroscope-std()-X                
#frequencyBodyGyroscope-std()-Y                 
#frequencyBodyGyroscope-std()-Z                
#frequencyBodyAccelerometerMagnitude-mean()     
#frequencyBodyAccelerometerMagnitude-std()     
#frequencyBodyAccelerometerJerkMagnitude-mean() 
#frequencyBodyAccelerometerJerkMagnitude-std() 
#frequencyBodyGyroscopeMagnitude-mean()         
#frequencyBodyGyroscopeMagnitude-std()         
#frequencyBodyGyroscopeJerkMagnitude-mean()     
#frequencyBodyGyroscopeJerkMagnitude-std()     
