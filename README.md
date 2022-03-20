# Predicting-diseases-using-Chest-XRay-using-Supervised-Learning

## COVID DETECTION USING SUPERVISED LEARNING ALGORITHMS

==================Procedure Followed=============================

1) Downloading and Unzipping the data from the dataset given

2) Importing Libraries required

3) Preprocessing the image dataset to obtain lung ROI

1.   Converting the image to gray image and applying gaussian filter
2.   Automatically finding threshold value using Otsu's thresholding
3.   Performing morphological operations : erosion and dilation
4.   Using midpoint ellipse to create a mask
5.   Applying the mask to obtain Region of Interest.

4) Finding first order and second order features of all the images for feature extraction.

5) Creating a function to take the preprocessed images from the four subfolders of four classes and saving a csv file with all the first and second order characterstics as features and label of images as output

6) Save preprocessed data to Google Drive to avoid multiple uploads in Colab.

7) Reading the preprocessed csv files and extracting respective features and labels.

8) Finding the supervised learning model accuracy and F1 score using:
1.	KNN
2.	Random Forest
3.	SVM

9) Conclusion


===========================END==========================================


