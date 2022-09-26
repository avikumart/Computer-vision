# Computer-vision

## Project 1: Image manipulation techniques

## Overview
Image dataset comes with large number of pixels, also can be called as a parameters in langauge of machine learning. while working with ML models for image dataset,often it is the case where you will have less data available to train models that generalise well for a new data input, you need more and more training data to build highly accurate model.

That's when data augementation or data generation comes into picture. data augementation nothing but variations of images that we already have. to generate more data out of existing data we leverage image manipulation techniques to transform, rotate, realign, rescale and crop data to generate more of them to feed to the algorithm.

In this notebook, I have shown some of the techniques to get familiar with image data and manipulate them which are used in data augmetation. keras has pre-defined methods to generate more images while building models.

## Techniques and approches
1) Importing libraries

2) Reading image data

3) Image reader function

4) Image manipulation techniques

5) Image similarity techniques

6) Image grouping techniques

7) Image classification

## Tools and technologies used:
- Skimage
- Sklearn 
- Numpy
- pandas
- matplotlib
- tqdm

---------------------------------------------

## Project 2: Intel Image classification project

### Web app link: https://avikumart-image-classification-web-app-rms-app-o1tcw1.streamlitapp.com/

## Overview
In this notebook, we will build image classification models to classify 6 categories of images; namely buildings, forest, glacier, mountain, sea, and street. image classification is one of the popular problems of computer vision challanges.

In this project of image classification we will try to build model from training dataset to classify and label images of six categories by users.

**Use-case:** Popular use-case of such model is image collections in mobile app wherein user captures images of scenaries, and model correctly labels & classifies into their respective class.

## Objectives and tasks:
1) Load the dataset and label them
2) Preprocess the Image dataset 
3) Build Image classification model using keras sequential API
4) Plot the loss and accuracy curve

## Action steps to solve this problem:
1) Loaded the dataset
2) Labeled the dataset
3) Visualized and explored the dataset
4) Trained the Deep neural net with CNN layers
5) Trained using pre-trained model VGG16 from keras models with feature extraction method
6) Classify unseen dataset of images into their respective class and label them

## Result:
1) I built 2 neural network models using CNN layers
2) first model's accuracy was at around 78% and second model's accuracy improved to 87% which is significant in this problem.
3) I learned aboout image classification techniques and feature extraction process of CNN from this project
3) I also deployed model using streamlit cloud to use this model for real world use-cases.




