Getting-and-Cleaning-Data-Assignment
====================================

Course Project 2

Assumptions made: 
1) Data is unzipped in the current working directory

Output:
tidyData.txt

Steps to execute:
1)Merge the training and the test sets to create one data set.
read into tables the data located in

features.txt
activity_labels.txt
subject_train.txt
x_train.txt
y_train.txt
subject_test.txt
x_test.txt
y_test.txt
Assign column names and merge to create one data set.

2)Extract only the measurements on the mean and standard deviation for each measurement.

Create a logcal vector that contains TRUE values for the ID, mean and stdev columns and FALSE values for the others. Subset this data to keep only the necessary columns.

3)Use descriptive activity names to name the activities in the data set

Merge data subset with the activityType table to cinlude the descriptive activity names

4)Appropriately label the data set with descriptive activity names.

Use gsub function for pattern replacement to clean up the data labels.

5)Create a second, independent tidy data set with the average of each variable for each activity and each subject.

tidyData.txt has the output of the above instruction.

