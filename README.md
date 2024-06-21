# PRODIGY_ML_03

Prodigy Machine Learning Internship Task-3

Implement a support vector machine (SVM) to classify images of cats and dogs from the Kaggle dataset.

Dataset: https://www.kaggle.com/c/dogs-vs-cats/data

## 1. Data Acquisition

- Connect Google Colaboratory with google drive and unpack the zip files
- Separate Images of Cats and Dogs

## 2. Data Preprocessing

- View grayscale images of cats and dogs alongside its original image
- Label the images for training, "0" for cat and "1" for dog
- Grayscale all images of cats and dogs, resize, normalize, and flatten it for getting features of them
- Applying (PCA) principal component analysis on this features

## 3. Model Training

- Split data into training set and test set
- Apply SVM with rbf kernel

## 4. Model Evaluation

- Predict the test set and find accuracy of model
- Create confusion matrix
- Take any image from test1.zip and convert it into features done above
- Predict if the image is of cat or dog
