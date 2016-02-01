# Getting-Cleaning-Data-Final-Project
Getting &amp; Cleaning Data Final Project
This file explains the steps taken to get, clean and create a tidy data set for the final project.
---------------------------------------------------------------------------------------------------

Step1: 	download the data from the URL given below
Step2: 	Unzip the downloaded data
Step3:	Store the paths of the files to a variable "path_rf" by using file.path function
Step4: 	Read the activity data from the files and store them in the variables "dataActivityTest" and "dataActivityTrain"
Step5: 	Read the Subject data files and store them in the variables "dataSubjectTrain" and "dataSubjectTest"
Step6: 	Read Features files and store them in the variables "dataFeaturesTest" and "dataFeaturesTrain"
Step7: 	Concatenate the Train and Test data tables  from steps 4-6 by rows and store them in variables
		"dataSubject", "dataActivity" and "dataFeatures"
Step8: 	Set the names to the variables in the three data sets
Step9: 	merge the three data tables into one data set by columns
tep10: 	Subset Name of Features by measurements on the mean and standard deviation
Step11:	Subset the data frame Data by the selected names of Features	
Step12:	Read descriptive activity names from “activity_labels.txt"
Step13:	Factorize variable activity in the data frame Data using descriptive activity names
Step14:	Label the data set with descriptive variable names
Step15: Create a second,independent tidy data set and output it
