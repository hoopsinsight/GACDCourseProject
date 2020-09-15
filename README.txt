==================================================================
Human Activity Recognition Using Smartphones Dataset - Modified
Version 1.0
==================================================================
Sean Vinsel for Coursera course "Getting and Cleaning Data"
Based on data from
Jorge L. Reyes-Ortiz, Davide Anguita, Alessandro Ghio, Luca Oneto.
Smartlab - Non Linear Complex Systems Laboratory
DITEN - Università degli Studi di Genova.
Via Opera Pia 11A, I-16145, Genoa, Italy.
activityrecognition@smartlab.ws
www.smartlab.ws
==================================================================

The obtained dataset was created by combining test and training data from the original data collection, selecting the subset of means and standard deviations of features, and taking the average for each subject/activity combination.
The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain. See 'features_info.txt' for more details. 

For each record it is provided:
======================================

- An identifier of the subject who carried out the experiment.
- Its activity label. 
- A 66-feature vector with time and frequency domain variables. 


The dataset includes the following files:
=========================================

- 'README.txt'

- 'CodeBook.md': Shows information about the variables used on the feature vector and the analysis performed.

- 'Course Project Data Set Vinsel.txt': Data set summarizing the average of all observations for the features, for each listed subject and activity


Notes: 
======
- Each feature vector is a row on the text file.
- This is based on the original dataset located at: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
- More information on the original data set can be found at: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones


