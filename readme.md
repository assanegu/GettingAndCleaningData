#Getting and Cleaning finalData Course Project

The goal of this project is to collect, clean the data set and create a tidy data set as as follow:

1. Merges the training and the test sets to create one data set.
 the data will be Merged as shown in the design bellow:

  1. test/subject_test.txt
  2. train/subject_train.txt
  3. test/X_test.txt
  4. train/X_train.txt
  5. test/y_test.txt
  6. train/y_train.txt


 ........................................................................  
 |............subject .......|.....activity........|.....feature.txt....|  
 ........................................................................  
 |.....subject_test.txt..... |.....y_test.txt .....|.....X_test.txt.....|  
 ........................................................................  
 |.....subject_test.txt..... |.....y_train.txt.....|.....X_test.txt.....|  
 ........................................................................  


2. Extracts only the measurements on the mean and standard deviation for each measurement. 

3. Uses descriptive activity names to name the activities in the data set

4. Appropriately remane the data set with descriptive variable names. 

5. From the data set in step 4, creates a second, independent tidy data set 

6. Generate a tidy data set named tidydatafile.txt