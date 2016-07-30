# Gettingandcleaningdata

This Readme file explains the analyssis carried out and the linkage of files.

Firstly, the file run_analysis.R contains the script with description of what each step in my programme does and how I move from raw data reading from link to the final tidy data.

The codebook file is a copy of the original features info provided in the assignment link with modifications to explain the variables in the run and the summaries. 

# Project Purpose
The purpose of this project is to demonstrate my ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 

# Project Objectives
To create one R script called run_analysis.R that does the following.

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# How the Code Works
The code works by copying thee data from the identified link (see code book) into a temp file. The temp file iss a zip file and so this is then unzipped and tables are read from train and test folders.
These tables are then assigned column names and also, variables "activities" and "participants" are connected to Y and Subject tables (both train and test)
Step1:The tables are merged into a Master table and duplicate column names omitted.
Step2:The master is used to extract mean and standrd deviation information
Step3: the variables are assigned descriptive activity names
Step4: The variables are assigned appropriate labels
Step5: Clean data is written into a txt file.
