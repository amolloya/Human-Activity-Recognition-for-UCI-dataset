# Human Activity Recognition for UCI Dataset

In this section, we use Human Activity Recognition (HAR) for classifying the daily activities performed by indivduals.

For HAR, Convolutional Neural Network has been proven to give real good results. We demonstrate this using Tensorflow in python on the UCI dataset. We use the convolutional neural net model inbuilt within tensorflow. </br> The code is available in the file: UCI-HAR.py

The input feature is a 561-feature vector with time and frequency domain variables obtained from the accelerometer and gyroscope signal by a device put on the user and the output is the corresponding activity label (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING). </br>
We achieve a good accuracy for this model with over 90% of the activities correctly classified.

Dataset available at: https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones
