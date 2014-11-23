coursera-getdata-project
========================

This repo explains how all of the scripts work and how they are connected.

Code to read the file in: (#source https://class.coursera.org/getdata-009/forum/thread?thread_id=58#post-177)

    data <- read.table(file_path, header = TRUE) 
    (#if they used some other way of saving the file than a default write.table, this step will be different)

    View(data)
    
    
Getting and Cleaning Data Course Project

run_analysis.R

Script does the following:

Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive activity names.
Creates a second, independent tidy data set with the average of each variable for each activity and each subject.





Acknowledgements

1) Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto.
Smartlab - Non Linear Complex Systems Laboratory
DITEN - Università degli Studi di Genova.
Via Opera Pia 11A, I-16145, Genoa, Italy.
activityrecognition@smartlab.ws
www.smartlab.ws


2) https://github.com/Vladimir84/coursera-get-data-002

3) https://class.coursera.org/getdata-009/forum/thread?thread_id=58#post-177

4) https://class.coursera.org/getdata-009/forum/thread?thread_id=204
    
 
