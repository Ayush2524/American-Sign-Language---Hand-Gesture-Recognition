Overview

This project aims to learn American Sign Language (ASL) hand gestures using a computer vision model that detects each gesture and also real-time detection in continuous motion.

Brief Procedure

Data Extraction from Kaggle and data exploration to identify the number of images per class in the dataset. The dataset included of characters from 0-9 and alphabets a-z.(Overall 36)

Cleaning of Data and landmarking the images using Mediapipe library and filtering out data which is fit to be trained later. 

Augmenting of data to balance the dataset across all classes and landmarking final images. 

Training the Model using RandomForest Classifier and analysed the metrics.

Test Accuracy of 92.45% and confusion matrix visualization to identify the misclassified pairs.
