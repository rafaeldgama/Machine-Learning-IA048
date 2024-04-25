Human Activity Recognition

Goal of this project:

In this project, we tackle the problem of Human Activity Recognition using the UCI HAR dataset, which is a database built from the recordings of 30 subjects performing activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors. Using its embedded accelerometer and gyroscope, the authors captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. 

The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). For this project, both the pre-processed sensor signals and the inertial signals (without any pre-processing) were used for the classification task.

I applied both Logistic Regression using softmax and kNN while varying its k value to determine the one that presented a best fit.
Furthermore, I used balanced accuracy as a performance metric and plotted the confusion matrix for the two models in both scenarios, pre-processed Data vs Raw Data.