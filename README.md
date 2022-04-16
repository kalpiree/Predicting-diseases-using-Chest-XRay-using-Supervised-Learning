# Predicting-diseases-using-Chest-XRay-using-Supervised-Learning

## COVID DETECTION USING SUPERVISED LEARNING ALGORITHMS

==================**Procedure Followed**=============================


> - Downloading and Unzipping the data from the dataset given

> - Importing Libraries required

> - Preprocessing the image dataset to obtain lung ROI

  >>  - Converting the image to gray image and applying gaussian filter.  
  >>  - Automatically finding threshold value using Otsu's thresholding.  
  >>   - Performing morphological operations : erosion and dilation.  
  >>   - Using midpoint ellipse to create a mask.  
  >>  - Applying the mask to obtain Region of Interest.  

> - Finding first order and second order features of all the images for feature extraction.

> - Creating a function to take the preprocessed images from the four subfolders of four classes and saving a csv file with all the first and second order characterstics as features and label of images as output

> - Save preprocessed data to Google Drive to avoid multiple uploads in Colab.

> - Reading the preprocessed csv files and extracting respective features and labels.

> - Finding the supervised learning model accuracy and F1 score using:
  >> -	KNN
  >> -	Random Forest
  >> -	SVM

> - Conclusion



## COVID DETECTION USING VGG-16
==================**Procedure Followed**=============================
> - Collecting the dataset from the link given.
> - Categorizing it based on different classes.
> - Designing the model.
> - Splitting the data into train, test and validation.
> - Data augmentation of the train images.
> - Training the model with two optimizers(adam, sgd).
> - Plotting the model accuracy and the loss.
> - Plotting the confusion matrix.


==========================**END**=================================


